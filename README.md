# Project-3 Проект по SQL: Анализ сервиса для чтения книг по подписке
**Описание проекта**

Ваша компания приобрела крупный сервис для чтения книг по подписке, и ваша первая задача как аналитика - проанализировать базу данных этого сервиса. База данных содержит информацию о книгах, издательствах, авторах, а также пользовательские обзоры книг. Эти данные помогут сформулировать ценностное предложение для нового продукта.

**Описание данных**

База данных содержит следующие таблицы:

**Таблица books**

Содержит данные о книгах:

- book_id — идентификатор книги;
- author_id — идентификатор автора;
- title — название книги;
- num_pages — количество страниц;
- publication_date — дата публикации книги;
- publisher_id — идентификатор издателя.

**Таблица authors**

Содержит данные об авторах:

- author_id — идентификатор автора;
- author — имя автора.

**Таблица publishers**

Содержит данные об издательствах:

- publisher_id — идентификатор издательства;
- publisher — название издательства.

**Таблица ratings**

Содержит данные о пользовательских оценках книг:

- rating_id — идентификатор оценки;
- book_id — идентификатор книги;
- username — имя пользователя, оставившего оценку;
- rating — оценка книги.

**Таблица reviews**

Содержит данные о пользовательских обзорах:

- review_id — идентификатор обзора;
- book_id — идентификатор книги;
- username — имя автора обзора;
- text — текст обзора.
  
**Как запустить проект**

Установите Jupyter Notebook или Jupyter Lab.

Откройте файл с проектом в Jupyter.

Запустите все ячейки по порядку.
