Определить структуру проекта
----------------------------

Для разработки проекта нужно сначала определить, что мы делаем и куда мы складываем, то что делаем, а ещё мы примерно представляем что нам понадобится.

Структура у нас такая

    /src
        /components - тут лежат все компоненты, которые мы разрабатываем
        /pages - тут лежат все страницы, которые мы отрисовываем
        /styles - тут лежат файлы стилей, скорее всего тут будет лежать только файл констант
        /resources - сюда складываем все используемые ресурсы (лого, картинки, моки и тд)

Не стоит забывать что 1 компонент может состоять из нескольких вложенных компонентов, как и вложенные компоненты могут состоять из ещё более мелких компонентов.
Аналогично со страницами. Иногда бывает удобно внутри страницы отрисовывать ещё 1 страницу, так как её содержание может сильно отличаться, например от типа пользователя.

В данном проекте, скорее всего, папка `styles` не понадобится.

Задача.
---------
Придумать структуру каждой папки. Для папки с компонентами - придумать структуру компонентов, для папки со страницами - структуру страниц и навигации между ними.

Всё это делается либо в виде структуры папок и файлов (шаблонных), либо в виде схемы дерева компонентов и страниц.

*Подсказка*. Создание макета в Figma очень сильно поможет разбить данный проект по компонентам и страницам.
