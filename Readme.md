# Инструкция для работы в Markdown

## Что такое Markdown?
Markdown - удобочитаемый язык разметки, который прозрачно конвертируется в HTML. Его можно открывать и изменять в любом редакторе текста. Широко используется для написания документаций и README-файлов.

## Заголовки
Для того, чтобы написать заголовок в Markdown, необходимо использовать знак# (хэш). Если необходимо несколько уровней заголовков, h1 - h6, нужно изменить количество хэшей (#) перед текстом заголовка. Например:
# H1
## H2
### H3
#### H4
##### H5
###### H6

## Выделение текста
Основное форматирование текста включает полужирный шрифт и курсив. Слова, выделенные курсивом, разделяются одной звёздочкой (*) или подчёркиванием (_). Например:
+ *Длинный_текст*
+ *Длинный текст*

Слова, выделенные полужирным шрифтом, разделяются двойной звёздочкой (**) или подчёркиванием (_).Например:
+ **Длинный текст**
+ **Длинный_текст**

Если необходимо зачеркнуть текст, то нужно поставит две тильды (~~) в начале и в конце фрагмента. Например:
+ ~~Законченное предложение~~


## Списки

### Маркированные списки
Для создания маркированных (ненумерованных) списков перед каждым пунктом нужно поставить минус (-), плюс (+) или звёздочку (*). Маркер и текст нобходимо разделять тексстом. Например:
- Текст
+ Абзац
* Параграф

### Упорядоченные списки
Если в качестве маркеров использовать цифры с точкой на конце (1., 2., и т.д.), то мы получим упорядоченный (нумерованный) список. Например:
1. Текст
2. Абзац
3. Параграф

### Вложенность
Любые списки можно вкладывать друг в друга, для этого перед маркером нужно поставить таб или несколько пробелов. Например:
+ Текст
    1. Предложения
    2. Словосочетания

* Абзац
    1. Переведённый
    2. Последний

## Списки задач
Создаются с использованием - [] для неотмеченных элементов, а - [х] для отмеченных элементов. Например:
- [] Основная задача
- [х] Главная задача

## Работа с изображениями

## Ссылки
Основной формат ссылки представляется в следующем ввиде: [Текст ссылки]. Например: [Markdown](https//markdown.com)

## Работа с таблицами

## Цитаты
Цитаты можно создать, начав строку с >символа "больше" (). Например:
>Век живи - век учись

>Без труда и не вытащищь рыбку из пруда

## Заключение