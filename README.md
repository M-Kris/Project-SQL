# Project-SQL

## Анализ базы данных книг и отзывов/обзоров на них

Коронавирус застал мир врасплох, изменив привычный порядок вещей. В свободное время жители городов больше не выходят на улицу, не посещают кафе и торговые центры. Зато стало больше времени для книг. Это заметили стартаперы — и бросились создавать приложения для тех, кто любит читать.

Ваша компания решила быть на волне и купила крупный сервис для чтения книг по подписке. Ваша первая задача как аналитика — проанализировать базу данных. В ней — информация о книгах, издательствах, авторах, а также пользовательские обзоры книг. Эти данные помогут сформулировать ценностное предложение для нового продукта.

**Цель проекта**: на основе информации в базе данных сформировать список наиболее популярных авторов книг и издательств, которые занимаются выпуском книг, а так же определение среднего количества обзоров от поьзователей с целью дальнейшего формирования предложения для пользователей и прогнозирования их активности.

|Название проекта| Описание | Библиотеки | Навыки и инструменты |
|:--|:--| :--: | :--: | 
|Анализ базы данных книг и отзывов на них| Анализ пользовательской активности для дальнейшего формирования предложения и разработки стратегии | pandas, sqlalchemy | SQL, PostgreSQL |

Результаты исследовательского анализа:
* 819 книг было выпущено после 1 января 2000 г.
* Издательство под названием Penguin Books выпустило наибольшее число книг (42) толще 50 страниц.
* Автор книг J.K. Rowling/Mary GrandPré имеет наибольшую среднюю оценку (4,29) своих произведений среди других авторов.
* В среднем 24 обзора делает пользователь на книги.
* с 1999 по 2007 гг. было выпущенно более 30 книг в год. При этом наблюдается ежегодная динамика к увеличению количества выпускаемых книг и рост издательств. В 2007 г. видно падение по данным показателям, при этом необходим дополнительный анализ, где необходимо перепроверить на сколько полны данные по этому году.
* Средний рейтинг книг с количеством отзывов более 3 незначительно больше общего среднего рейтинга, разница составляет 0,021 балла.
