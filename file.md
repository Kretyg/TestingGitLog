# Инструкция по работе с Git.

Начальная работа с системой контроля версий. 

*git --version* - команда для проверки версии git.

*git init* - инициализация пустого репозитория.

*git status* - проверка текущего состояния файлов.

*git add* - добавление версионности файлу.

*git commit -m "Сообщение"* - команда для фиксации изменений файлов.

*git log* - вывод истории комитов в хронологическом порядке.

*git diff* - вывод изменений на текущий момент по отношению к последнему комиту.

*git checkout master* или *git checkout хеш-номер_комита* - переход между изменениями либо возврат к текущему состоянию.

*fork* чужая копия.

*git clone <url-адрес репозитория>* - клонирование внешнего репозитория на локальный ПК.

*git pull* - получение изменений и слияние с локальным репозиторием.

*git push* - отправляет локальную версию репозитория на внешний.

*git remote set-uol origin<url-адрес репозитория>* - сбрасывает линк с предыдущего репозитория. Необходимо при перепривязке нового адреса на локальный репозиторий.

# Работа с C# через GIT 

## Комманды в терминале

*dotnet new consoloe* - создать новый проект

*dotnet run* - запустить проект (Через Console мы обращаемся к системному терминалу)

## Команды в записной строке

*Write()* Вывод в одну строку

*WriteLine()* В конце перейти на новую строну

*ReadLine()* Считать строку из терминала

*new Random().Next(min, max)* Случайности или даст случайное целое число от min до max-1 (min, max-1) или (min, max)

*if and else and while* Синтаксис и его начало
             if(Условие)                while(Условие прожолжени
             {                          {
               Набор действий 1           Набор действий
             }                          }
             else
             {                          int count = 0;
               Набор действий 2
             }                          while(count<100)
                                        {
                                          Набордействий
                                          count = count + 1
                                        }

## Добавление разметки MarkDown

## Заголовки
Язык разметки Markdown поддерживает 2 стиля обозначения заголовков: подчеркивание и выделение символом («#»).
Выделение заголовков с помощью подчеркивания производится знаками равенства («=») в случае, если заголовок
первого уровня, и дефисами («-») в случае, если заголовок второго уровня. Количество знаков подчеркивания не
ограничивается. При выделении заголовков с помощью символа («#») используется от одного до шести данных символов,
которые устанавливаются в начале строки (перед заголовком). В данном случае количество символов соответствует
уровню заголовка. Кроме того, заголовок возможно снабдить закрывающимися символами («#»), хотя это и не является
обязательным. Количество закрывающихся символов не обязано соответствовать количеству начальных символов.
Уровень заголовка определяется по количеству начальных символов.
Заголовки первого и второго уровней, выполненные с помощью подчеркивания, выглядят следующим образом:
Заголовок первого уровня
========================
Заголовок второго уровня
-------------------------
Заголовки первого, третьего и шестого уровней, выполненные с помощью символа («#»), выглядят следующим образом:
# Заголовок первого уровня
### Заголовок третьего уровня
###### Заголовок шестого уровня
Приведенные выше заголовки, выполненные с помощью символа («#») тождественны следующим:
# Заголовок первого уровня #
### Заголовок третьего уровня ###
###### Заголовок шестого уровня ######

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

Картинка без alt текста
Картинка с альтом и тайтлом:
Alt text
Запомнить просто: синтаксис как у ссылок, только перед
открывающей квадратной скобкой ставится восклицательный знак.
Картинки «сноски»: Картинки
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
## Использование HTML внутри Markdown
Картинка Картинка Картинка
Картинки-ссылки:
Alt text (http://example.com/)
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

новая запись с даленного репозитория 1
могу теперь с телефона 
