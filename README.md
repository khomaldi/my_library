Это моя библиотека.

Для меня это самый простой способ вести учёт книг.

Вся документация ниже ↓

## Author

`id: string` — UUID V7. Генерируется мной вручную при добавлении в библиотеку.

`name: string` — Полное имя автора.


## Book

`id: string` — UUID V7. Генерируется мной вручную при добавлении в библиотеку.

`title: string` — Название книги.

`author_ids: array<string>` — Список ID авторов.

`read: bool` — Прочитана ли книга.

`rating: float?[1.0..10.0, step 0.1]` — Оценка книги.

`started: string` — Начало чтения.

`finished: string` — Конец чтения.

`publication_year: number` — Год издания этого тиража.

`publication_country: string` — Страна издания этого тиража.

`publisher_id: string` — ID издательства.

`isbn: string` — ISBN.

`cover_url: string` — Ссылка на изображение обложки книги.

`category_ids: array<string>` — Список ID категорий, к которым относится книга.

`ebook_id: string` — ID электронное версии книги.


## Category

`id: string` — UUID V7. Генерируется мной вручную при добавлении в библиотеку.

`name: string` — Название категории.


## Publisher

`id: string` — UUID V7. Генерируется мной вручную при добавлении в библиотеку.

`name: string` — Название издательства.

`website: string` — Официальный сайт издательства.
