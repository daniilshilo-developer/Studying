# Studying

Репозиторий, в котором содержатся мои заметки по изучение чего-то нового.

## Принципы ведения данного репозитория
Дело в том, что неудобно учить всё _подряд_. Мне неудобно так вести заметки, поэтому я решил создать новую систему, более гибкую и быструю.

В каждой папке собраны файлы с информацией о какой-либо теме и её подтеме. Если тема основная, то она _не ссылается на другие темы_, то есть рассказана так, чтобы с неё можно было начинать изучать что-то.
Если у файла есть _подтема_, то он обязательно будет ссылаться на основные темы. Основных тем может быть несколько.

Например:

Тема: `2-Sass_переменные.md`, начинаться данный файл будет так:
```markdown
# Связные темы
* [Sass](2-Sass.md)
* [CSS](1-CSS.md)
* [CSS: Переменные](1-CSS_variables.md)

# Переменные в SASS
..
```

Как можно увидеть данная модульная система ссылок на источники, которые нужно изучить перед тем, как приступать к изучению основной темы даёт мне возможность не писать всё об HTML, чтобы потом рассказать для чего нужен CSS, а просто указать источники, которые я посчитаю нужными. Я даже могу не писать ничего про HTML, в данном случае он просто не причём..

Если бы я вёл линейный дневник изучения, то мне бы пришлось рассматривать HTML, CSS, DOM, Фреймворки CSS, SASS, а так я просто могу сразу начать писать о теме не давая вам лишней информации и не напрягая себя переписывать то, что я уже знаю, или то что легко нагуглить.

### Условные обозначения имён файлов
В основном файлы в данном репозитории названы руководствуясь следующей схемой: `Сложность-Тема_подтема.md`

Если где-то данная схема соблюдаться не будет, то в локальном файле директории `README.md` будет указано на несоответствие.


# Доступные директории

* [Javascript](/javascript)
* [Vim](/vim)

# Темы, которые мне нужно выучить или затронуть

| Тема                                                          | Сложность | Теги                 | Изучена (если да, то предоставляется ссылка) |
|:------------------------------------------------------------- |:---------:|:--------------------:|:--------------------------------------------:|
| HTTP                                                          | 1         | #internet, #networks | [Да](https://github.com/daniilshilo-developer/Studying/tree/master/http)|
| HTTPS                                                         | 1         | #internet, #networks | Нет                                          |
| Работа с DOM посредством JavaScript                           | 2         | #javascript          | Нет                                          |
| Взаимодействие с API с помощью Fetch API или подобных средств | 3         | #API                 | Нет                                          |
| CSS Grid                                                      | 3         | #css                 | Нет                                          |
| Flexbox                                                       | 2         | #css                 | Нет                                          |
| Async / Await                                                 | 4         | #javascript          | Нет                                          |
| JSON                                                          | 2         | #javascript          | Нет                                          |
| Jest                                                          | 3         | #javascript          | Нет                                          |
| Создание API для фронтенда (обычно с помощью JSON)            | 2         | #php #javascript     | Нет                                          |
| Шаблоны разработки                                            | 5         | #templates           | Нет                                          |
| Продвинутое использование Vim                                 | 3         | #vim                 | Нет                                          |
