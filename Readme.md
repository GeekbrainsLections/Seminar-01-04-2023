# Инструкция по работе с *Markdown*

## Создание заголовков в языке *Markdown*
Для того, чтобы создать заголовок в языке *Markdown*, необходимо в начале строки написать несколько символов #. Количество символов # показывае уровень заголовка. Чем меньше уровень заголовка, тем больше текст(как в печате газет).

## Форматирование текста в языке *Markdown*
Для того, чтобы написать *курсивные текст*, необходимо этот текст поместить между двумя символами звёздочка, для **жирного текста** - между двумя парами звёздочек. ***Для курсивного жирного текста***, текст надо написать между двумя тройками звёздочек. Для написания ~~зачёркнутого~~ текста необходимо этот текст обрамить звумя парами символов ~(тильда).

Списки в языке *Markdown*
---------------------------
Списки в языке *Markdown* бывают:
+ Нумерованные
+ Ненумерованные
Для создания элемента нумерованного списка, перед текстом необходимо написать его номер в списке и поставить точку, например, 

Список продуктов:
1. Молоко
2. Яйца
3. Хлеб
Для создания элементов ненумерованного списка, перед элементом списка необходимо поставить любой из сиволов: +, -. 

Например, список продуктов:
+ Молоко
+ Яйца
+ Хлеб

## Ссылки в *Markdown*
Для добавления ссылки в языке *Markdown* необходимо написать в квадратных скобках текст ссылки, и рядом в круглых скобках адрес ссылки., например [Github](https://github.com)

## Цитаты

Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак `>` ставится перед каждым элементом цитаты, будь то абзац, заголовок или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе вложенные цитаты:

> ## This is a header.
>
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");