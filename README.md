
# Проект "Закрывающий тег"
***
## Структура сайта
Семантически сайт поделен на несколько блоков и секций:
__Блок Header__ - шапка сайта. Здесь находятся кнопки выбора переключения тем сайта: "темно", "авто", "светло". Функционал переключения реализован с помощью js (файл set-theme.js);
__Блок main__ - Основное содержимое страницы;
__Блок footer__ - подвал сайта

***
## Функционал проекта
### 1. Организация файлов в проекте
Проект создан по методологии БЭМ, аайловая структура в реализована по схеме Nested:
* Каталог styles - содержит блоки проекта, модификаторы и элементы;
* Каталог scripts - содержит JS скрипты, используемые в проекте;
* Каталог pages - содержит файл Index.css, в котором указанны ссылки на все CSS стили проекта;
* Каталог fonts - содержит подключаемые шрифты.
* Каталог images - содержит картинки, используемые на сайте.

### 2. Используемые технологии
Все элементы страницы хранятся в родительском блоке `body`.
В проекте используется файл `variables.css`, в указываются переменные проекта, а именно - большинство цветов, шрифт, размеры текста для разных элементов и отступы.

В файле `themes.css` указаны переменные для темной и светлой темы сайта.

В файле `globals.css` находятся глобальные стили для всего проекта.

В проекте используются  шрифтs  `PressStart2P` и `Inter`. Шрифт `Inter` вариативный.

Благодаря адаптивной верстке сайт подстраивается под различные разрешения экрана.

### 4. Ссылки
Сайт - [Закрывающий тег](https://sergey-pyschkin.github.io/zakrivayuschiy-teg-f/index.html)

# zakrivayuschiy-teg-f
