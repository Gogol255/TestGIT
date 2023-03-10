# Инструкция по работе с Git

Начальная работа с системой контроля версий.

*git version* - команда для проверки версии 

*git init* - инициализация пустого репозитория

*git statys* - проверка текущего состояния файлов

*git add* - добавление версионности файлу

*git commit -m"Сообщения"- команда для фиксации изменений файлов

*git log* - вывод истории комитов в хронологическом порядке

*git diff* - вывод изменений на текущий момент по отношению к последнему комиту

*git checkout* *git checkout master*- перход между изменениями либо возврат к текущему состоянию

## Добавление разметки MarkDown

## Заголовки

Заголовки отмечаются диезом `#` в начале строки, от
одного до шести. Например:
# Заголовок первого уровня  
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6
В декоративных целях заголовки можно «закрывать» с
обратной стороны.

## Ссылки

Это встроенная [ссылка с title элементом]

(http://example.com/link "Я ссылка"). 
Это — [без title]
(http://example.com/link).

А вот [пример][1] [нескольких][2] [ссылок][id] с
разметкой как у сносок.
 Прокатит и [короткая запись][]
без указания id.

[1]: http://example.com/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short

Вынос длинных урлов из предложения способствует
сохранению читабельности исходника. Сноски можно
располагать в любом месте документа.

## Картинки

![logo](logo.png)

## Таблицы
В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.

| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.

Для всего остального есть обычный HTML.
Картинка без `alt` текста
![](//placehold.it/150x100)

Картинка с альтом и тайтлом:
![Alt text](//placehold.it/150x100 "Можно задать title")

Запомнить просто: синтаксис как у ссылок, только перед
открывающей квадратной скобкой ставится восклицательный
знак.

Картинки «сноски»:
![Картинка][image1]
![Картинка][image2]
![Картинка][image3]

[image1]: //placehold.it/250x100
[image2]: //placehold.it/200x100
[image3]: //placehold.it/150x100

Картинки-ссылки:
[![Alt text](//placehold.it/150x100)]
(http://example.com/)

## Цитаты

Что разум человека может постигнуть и во что он может поверить, того он способен достичь

Наполеон Хилл, журналист и писатель 

Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак `>` ставится
перед каждым элементом цитаты, будь то абзац, заголовок
или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.