# Шпаргалка по Markdown
**_Markdown_** - это облегченный язык разметки с синтаксисом форматирования обычного текста.
# Заголовки
Заголовки в Markdown выделяются с помощью знаков решетки. Можно просто поставить нужное кол-во решеток в начале строки, чтобы показать уровень. Не забываем ставить пробел после знака #.

# Заголовок 1
## Заголовок 2
### Заголовок 3
#### Заголовок 4
##### Заголовок 5
###### Заголовок 6

    Заголовки первого и второго порядка можно также выделять с помощью знаков "=" и "-"

Заголовок первого порядка выделяем знаками "равно" после написания заголовка и нажатия клавиши Enter
====
Заголовки второго порядка выделяем знаками "дефис" после написания и нажатия клавиши Enter
-----

# Выделение текста
Есть следующие виды форматирования текста: курсивом, жирным, зачеркнутым и комбинированным. Синтаксис выделения текста и расставления акцентов:
* Для выделения текста жирным используем знаки "__" или "**", например, **текст** или __текст__
* Для выделения текста курсивом используем знаки "-" или "*", например, _текст_ или *текст*
* Для выделения текста зачеркиванием используем знаки"~~", например, ~~текст~~ 
* Также можно одновременно использовать различные акценты для двойного выделения текста, например, чтобы выделить текст одновремнно курсивом и жирным используем разные акценты для каждого из форматирований (например, * для курсива и __ для жирного),  *__текст__*.

# Списки и отступы
Списки бывают *ненумерованные* и *нумерованные*.

Для создания ненумерованного списка в начале строки необходимо поставить "+", "-" или "*". Не забываем отделть знак от последующего слова пробелом:
+ Элемент 1
- Элемент 2
* Элемент 3

Для создания нумерованного списка в начале строки ставим цифру с точкой.
1. Элемент 1
2. Элемент 2
3. Элемент 3

Также возможно создание многоуровневых списков, тогда каждый новый подпункт выделяем табуляцией:
1. Элемент 1
    * Элемент 2
        + Элемент 3

# Ссылки и картинки
* Чтобы поставить гиперссылку без анкора, нужно взять URL в угловые скобки *<>*:

<https://gb.ru/>
* Если вставлять с анкором, то текст ссылки заключается в квадратные скобки "[]", а адрес страницы в круглые "()":

[Ссылка на образовательный портал](https://gb.ru/)
* Рядом с URL можно прописать тайтл, его объявляют в кавычках (он остается внутри круглых скобок):

[Ссылка на образовательный портал](https://gb.ru "GeekBrains")

Для работы с изображением используется похожий синтаксис. Текст ссылки на картинку заключается в квадратные скобки"[]", перед которым ставим восклицательный знак "!", а сама ссылка на картинку заключается в круглые скобки "()" (в них указываем имя файла.расширение): 

![Хочу на море](Море.jpg)

# Цитаты
Для оформления цитат исползуем одну угловую скобку ">" (для обозначения вложенности увеличиваем кол-во угловых скобок):
> А судьи кто?
>> Скажи-ка дядя ведь недаром...

# Таблицы
Если поддерживается расширенная версия Markdown, можно вставлять таблицы. Для этого используются всего два символа: верикальная черта "|" (служит границей между столбцами) и дефис "-" (отделяет заголовки от других строк):
|Птицы|Рыбы
|--|--|
|Голубь|Карась 
|Воробей|Окунь

Но у нас это почему-то несовсем работает )

**Мы с вами составили небольшую инструкцию по использованию языка разметки Markdown и разобрали с десяток различных символов, которые используются в разметке.**
