#### Лабораторная работа №5. Введение в HTML
**ФИО**: Катаржин Г.М.
**Группа**: ИСП-232
**Дата**: 27.01.2026
#### Описание работы
В данной лабораторной работе создаётся проект для изучения основ HTML.
Вы настраиваете рабочую директорию, создаёте базовые файлы, подключаете Git и GitHub, а также подготавливаете HTML-файл для последующего изучения структуры веб-страницы.
### Что изучили
- Структура HTML-документа
- Базовые теги: заголовки, абзацы, выделения (`<strong>`, `<em>`), переносы (`<br>`), разделители (`<hr>`)
- Работа со ссылками (`<a>`) и изображениями (`<img>`)
- Нумерованные (`<ol>`) и маркированные (`<ul>`) списки, в том числе вложенные
- Атрибуты HTML-элементов: `id`, `class`, `title`, `src`, `alt`, `href`, `target`, `placeholder` и др.
- Таблицы (`<table>`, `<tr>`, `<td>`)
- Формы и элементы ввода (`<form>`, `<input>`, `<textarea>`, `<select>`, `<label>`, `<button>`)
- Семантические теги HTML5: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Валидация HTML-кода с помощью W3C Validator
#### Структура проекта
* **index.html** — основной HTML-файл
* **README.md** — описание лабораторной работы
* **img/** — скриншоты
* **index2.html** - пример семантической разметки
* **about.html** - страница "О себе" с семантическими тегами
* **webpageCard.html** - веб-визитка
## Теги и элементы
### Теги в HTML
структура парного тега:
**<тег>тело<тег>**
Пример:
```HTML
<h1>Это заголовок</h1>
```
 ### Базовые HTML-теги
 ### Примеры:
```html
<h2>Заголовок</h2>
<p>Абзац текста</p>
<strong>Жирный</strong>
<em>Курсив</em>
<hr>
<a href="https://example.com">Ссылка</a>
<img src="example.jpg" alt="Описание">
```
### Основные теги
```html
<h1>Заголовок первого уровня</h1>
<h2>Заголовок второго уровня</h2>
<p>Абзац текста</p>
<strong>Жирный текст (важность)</strong>
<em>Курсив (акцент)</em>
<br> — перенос строки
<hr> — горизонтальная линия
<a href="https://github.com">Ссылка на GitHub</a>
<img src="img/example.jpg" alt="Пример изображения">
```
### Списки
```html
<ol>
  <li>Фильм 1</li>
  <li>Фильм 2</li>
</ol>

<ul>
  <li>Хобби 1</li>
  <li>Хобби 2</li>
</ul>

<ul>
  <li>Родительский пункт
    <ul>
      <li>Вложенный пункт</li>
    </ul>
  </li>
</ul>
```
### Атрибуты
```html
<p id="intro" class="text main" title="Вводный абзац">Текст с атрибутами</p>
<a href="https://example.com" target="_blank">Открыть в новой вкладке</a>
<img src="img/pic1.png" alt="Локальное изображение" width="200">
<input type="text" placeholder="Введите ваш город">
<button title="Отправить форму">Отправить</button>
```
### Таблица
```html
<table border="1">
        <tr>
            <td>ФИО</td>
            <td>Катаржин Григорий Михайлович</td>
        </tr>
        <tr>
            <td>Группа</td>
            <td>ИСП-232</td>
        </tr>
        <tr>
            <td>Любимый язык программирования</td>
            <td>Python</td>
        </tr>
        <tr>
            <td>Город</td>
            <td>Волжский</td>
        </tr>
    </table>
```
### Форма
```html
<form>
        <label for="username">Имя: </label>
        <input id="username" type="text" placeholder="Введите имя">
        <br><br>
        <label for="email">Email:</label>
        <input id="email" type="email" placeholder="example@mail.com">
        <br><br>
        <label for="city">Город: </label>
        <select id="city">
            <option>Волгоград</option>
            <option>Волжский</option>
            <option>Камышин</option>
        </select>
        <br><br>
        <label for="message">Cообщение: </label>
        <textarea id="message" rows="4" placeholder="Напишите текст..."></textarea>
        <br><br>
        <button type="submit">Отправить</button>
    </form>
```
### Семантическая разметка
```html
 <header>
    <h1>Лабораторная работа №5</h1>
    <nav>
        <a href="#">Главная</a>
        <a href="#">Форма</a>
        <a href="#">Контакты</a>
    </nav>
</header>

<section>
    <h2>Обо мне</h2>
    <p>Меня зовут Гриша. Я изучаю основы HTML.</p>
    
    <h2>Полезная информация</h2>

    <h3>Статья 1</h3>
    <p>Текст первой статьи.</p>

    <h3>Статья 2</h3>
    <p>Текст второй статьи.</p>
</section>

<footer>
    © 2025 | Катаржин Григорий Михайлович | ИСП-232
</footer>
```
