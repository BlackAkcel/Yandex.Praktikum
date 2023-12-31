# [Проект по SQL](https://github.com/BlackAkcel/Yandex.Praktikum/blob/main/Final/Final_3/sql.ipynb)
## Сферы деятельности
Онлайн-Сервисы, Маркет-плейс
## Направления деятельности
`Аналитик(универсал)`, `Data Analyst`

## Результаты исследования
1. Изучены особенности базы данных.
2. Даны рекомендации по развитию сервиса.


## Описание проекта

Я являюсь аналитиком кампании, решившей заняться сервисом по предоставлению чтения книг по подписки.

У меня есть доступ к базе данных сервиса, и моя задача проанализировать её.

## Описание данных

В БД хранятся следующие таблице

**Таблица** `books` cодержит данные о книгах:
+ `book_id` — идентификатор книги;
+ `author_id` — идентификатор автора;
+ `title` — название книги;
+ `num_pages` — количество страниц;
+ `publication_date` — дата публикации книги;
+ `publisher_id` — идентификатор издателя.

**Таблица** `authors` содержит информацию об авторах:
+ `author_id` — идентификатор автора;
+ `author` — имя автора.

**Таблица** `publishers` содержит данные об издательствах:
+ `publisher_id` — идентификатор издательства;
+ `publisher` — название издательства;

**Таблица** `ratings` cодержит данные о пользовательских оценках книг:
+ `rating_id` — идентификатор оценки;
+ `book_id` — идентификатор книги;
+ `username` — имя пользователя, оставившего оценку;
+ `rating` — оценка книги.

**Таблица** `reviews` cодержит данные о пользовательских обзорах:

+ `review_id` — идентификатор обзора;
+ `book_id` — идентификатор книги;
+ `username` — имя автора обзора;
+ `text` — текст обзора.

### Схема данных

![Alt Text](https://pictures.s3.yandex.net/resources/scheme_1589269096.png)

## Цели исследования

Подготовить рекомендации по развитию сервиса на основе изучения базы данных.
