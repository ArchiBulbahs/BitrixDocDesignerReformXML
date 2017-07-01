# BitrixDocDesignerReformXML
Программа для устранения ошибок переменных в шаблонах docx (конструктор документов bitrix коробочная версия).

## Предназначение 
Данная программа исправляет разрывы переменных при формировании шаблона в файле DOCX.
Проявляются эти разрывы таким образом что при формировании документа в Bitrix24 некоторые или все переменные на выводят необходимое содержимое полей(тоесть в документе остаются сами переменные).

## Использование программы

1. Интерфейс:

2. Для загрузки файла в программу необходимо нажать на кнопку "Открыть XML". После нажатия на кнопку откроется диалоговое окно в котором необходимо будет выбрать необходимый файл.

3. После того как вы открыли нужный файл необходимо нажать на кнопку "Начать". После нажатия на кнопку "Начать" программа зависнет, но ProgressBar будет бегать, что означает что программа работает. По завершению обработки и исправлению ошибок в Textbox будут выведены XML кода:

3.1. Разбитый XML.

3.2. Разбитый исправленный XML.

3.3. Конечный XML (готовый и скомпанованный).

4. После того как обработка выполнена, можно сохранить готовый XML в Файл нажатием кнопки "Сохранить в XML" или же просто скопировать XML код и заменить в необходимом файле.



##
Данная программа была разработанна для личного использования, из-за этого в программе присутствуют недоработки.
Если программа будет актуальна,то я будут производиться ее доработки.
Если буду продолжать разработку изменю следующие моменты:
1. Изменю интерфейс.
2. Сделаю загрузку не XML файла, а DOCX формата. Соответственно сохранение тоже сделаю в DOCX формат.
3. Стабилизирую обработку XML кода (уберу подвисание программы).
Если будут пожелания по доработке данной программы пишите мне на почту archibulbash@gmail.com (Тема сообщения "BitrixDocDesignerReformXML").
