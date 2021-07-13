# Состояния в Гит

У Гита есть несколько состояний, которые нужно понять и запомнить:

***неотслеживаемое*** (untracked);

***измененное*** (modified);

***подготовленное*** (staged);

***закомиченное*** (committed).

## Как это понимать?

Это состояния, в которых находятся файлы из нашего кода. То есть, их жизненный путь обычно выглядит так:

1. Файл, который создан и не добавлен в репозиторий, будет в состоянии *untracked*.
2. Делаем изменения в файлах, которые уже добавлены в гит репозиторий — находятся в состоянии *modified*.
3. Из тех файлов, которые мы изменили, выбираем только те (или все), которые нужны нам (например, скомпилированные классы нам не нужны), и эти классы с изменениями попадают в состояние *staged*.
4. Из заготовленных файлов из состояния *staged* создается коммит и переходит уже в гит репозиторий. После этого *staged* состояние — пустое. А вот *modified* еще может что-то содержать.
![states](./assets/800.png)