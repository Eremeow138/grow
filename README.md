# HTML
## HTML / Layout and text formatting tags
- ### Layout tags

  Семантическая разметка несет поисковым роботам, браузерам и программам-ридерам (чтецам) информацию о типе, важности и акцентировании контентного содержания html-документа для облегчения его машинной обработки.

  **HTML** имеет несколько семантических тегов, которые определяют различные части веб-страницы:
  ![image](https://user-images.githubusercontent.com/60056105/140636230-eac97dba-10d2-4948-b9c1-efae1445bccc.png)
  -	`<header>` - Определяет **Заголовок** для документа или `<section>`
  -	`<nav>` - Определяет набор навигационных ссылок
  -	`<section>` - Определяет секцию (раздел) в документе
  -	`<article>` - Определяет независимый, самостоятельный контент
  -	`<aside>` - Определяет контент сбоку от основного контента (например **sidebar**)
  -	`<footer>` - Определяет **Подвал** для документа или `<section>`

- ### HTML 5 structural and semantic tags

  Список популярных семантических тегов:
  - `<article>`	Определяет статью
  - `<aside>`	Определяет блок сбоку от основного контента
  - `<details>`	Определяет дополнительную информацию, которую пользователь может открывать или закрывать
  - `<figcaption>`	Определяет пояснение для элемента `<figure>`
  - `<figure>`	Используется для группирования различных самодостаточных элементов - иллюстраций, диаграмм, фотографий, листингов кода и т.д.
  - `<footer>`	Определяет "подвал" документа или раздела
  - `<header>`	Определяет "шапку" документа или раздела
  - `<main>`	Определяет основной контент документа
  - `<mark>`	Определяет маркированный/подсвеченный текст
  - `<nav>`	Определяет блок навигационных ссылок
  - `<section>`	Определяет раздел в документе
  - `<summary>`	Определяет видимый заголовок элемента `<details>`
  - `<time>`	Определяет дату/время

- ### Formatting tags

  Форматирование делится на визуальное и логическое. За визуальное форматирование отвечают теги визуального форматирования, за логическое — теги логического форматирования. Последние называют ещё семантическими.
  К тегам визуального форматирования относятся:
  - `<span>`
  -	`<mark>`
  -	`<br>` и `<wbr>`
  -	`<i>`
  -	`<b>`
  -	`<sup>` и `<sub>`
  -	`<ruby>`
  -	`<u>`
  -	`<s>`

  А это список тегов логического форматирования:
  -	`<a>`
  -	`<em>`
  -	`<strong>`
  -	`<cite>`
  -	`<code>`
  -	`<abbr>`
  -	`<dfn>`
  -	`<ins>`
  -	`<del>`
  -	`<q>`
  -	`<kbd>`
  -	`<samp>`
  -	`<var>`
  -	`<time>`
  -	`<small>`
  -	`<bdi>` и `<bdo>`

  **Семантика** против **Визульного форматирования**

    - `<em></em>` и `<i></i>`

      Визуально эффект одинаковый: текст внутри тега станет *курсивным*, но в случае с тегом `<em>`  *Скринридер* прочитает текст внутри с эмоциональным акцентом и подчеркнет его эмоциональную важность. Когда мы говорим, то делаем это при помощи интонации и громкости. В вебе для этого есть тег em.
      **em (emphasis)** — эмфатическое ударение.
      Эмфатическое ударение — выделение слова интонацией для усиления эмоциональной выразительности.

    - `<strong></strong>` и `<b></b>`

      `<strong></strong>` — логическое ударение.

      Логическое ударение — выделение слова интонацией для усиления его смысла или повышения значимости.

      С помощью `<strong>` подчёркивают важность слов и предложений. Пользователь увидит такой текст полужирным, а скринридеры выделят интонацией.

      `<b>` (bold) делает текст полужирным. Тег `<b>` используют для визуального форматирования. Он не усиливает смысловой вес слов, в отличие от strong.
      Почитать больше о тегах форматирования можно [тут](https://medium.com/@fokinatatiana/%D1%84%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D1%8B%D0%B5-%D1%82%D0%B5%D0%B3%D0%B8-%D0%B2-html-1b71f0b047).

- ### Table

  Таблицы в языке **Html** являются особенным элементом, ибо по своей сути элемент **Table** является блочным, но при этом он не занимает все доступное ему по ширине пространство, как это делают другие блочные элементы. По ширине он занимает лишь то пространство, которое необходимо для размещения содержимого — ни больше, ни меньше. Идущие в коде друг за другом таблички будут на вебстранице располагаться друг под другом.

  Вся таблица обрамляется открывающим и закрывающим тегами **Table**, внутри которых с помощью **Tr** создаются ее строки, а вот уже внутри **Tr** создаются ячейки с помощью **Td**.
  Содержимое (контент) ячейки, созданной с помощью тега **Td**, будет выровнено по левому краю, а содержимое ячейки, созданной с помощью **Th**, будет выровнено по центру и к тому же выделено полужирным начертанием используемого шрифта.
![image](https://user-images.githubusercontent.com/60056105/141041740-b8f9d7e4-0980-4cb8-86fd-6e8d1e16c250.png)
