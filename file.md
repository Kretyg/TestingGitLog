# Инструкция по работе с Git.

Начальная работа с системой контроля версий. 

*git --version* - команда для проверки версии git

*git init* - инициализация пустого репозитория

*git status* - проверка текущего состояния файлов

*git add* - добавление версионности файлу

*git commit -m "Сообщение"* - команда для фиксации изменений файлов

*git log* - вывод истории комитов в хронологическом порядке

*git diff* - вывод изменений на текущий момент по отношению к последнему комиту

*git checkout master* или *git checkout хеш-номер_комита* - переход между изменениями либо возврат к текущему состоянию

*fork* чужая копия 

## Добавление разметки MarkDown

## Заголовки

## Ссылки 

Это встроенная ссылка с title элементом (http://example.com/link). Это
— без title (http://example.com/link).
А вот пример (http://example.com/) нескольких
(http://example.com/some) ссылок (http://example.com/links) с
разметкой как у сносок. Прокатит и короткая запись
(http://example.com/short) без указания id.
Вынос длинных урлов из предложения способствует сохранению
читабельности исходника. Сноски можно располагать в любом месте
документа.

## Картинки

## Таблицы
В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.
Mожно смешивать Markdown и HTML. Если на какие-то
элементы нужно поставить классы или атрибуты, смело
используем HTML:
> Выделять слова можно при помощи * и _ . Например, это
<em class="a1">italic</em> и это тоже <i
class="a1">italic</i>. А вот так уже <b>strong</b>, и
так тоже <strong>strong</strong>.
Можно и наоборот, внутри HTML-тегов использовать
Маркдаун.
<section class="someclass">
### Пример Маркдауна внутри HTML
Выделять слова можно при помощи `*` и `_` . Например,
это _italic_ и это тоже *italic*. А вот так уже
__strong__, и так тоже **strong**.
</section>
### Таблицы
В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.
First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:
First Header Second Header
Content Cell Content Cell
Content Cell Content Cell
Для красоты можно и по бокам линии нарисовать:
First Header Second Header
Content Cell Content Cell
Content Cell Content Cell
Можно управлять выравниванием столбцов при помощи двоеточия.
Left-Aligned Center Aligned Right Aligned
col 3 is some wordy text $1600
col 2 is centered $12
zebra stripes are neat $1
Внутри таблиц можно использовать ссылки, наклонный, жирный или
зачеркнутый текст.
Для всего остального есть обычный HTML.
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