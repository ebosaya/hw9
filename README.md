## ЧАСТЬ 1 . 
Судя по структуре текста  все пустые строки объеденяются в следующие  блоки:
*перенос строки
*пробел+перенос строки
*перенос строки


*Скриншот 1
Для замены таких блоков используем в программе Notepad++ регулярное выражение "\r\n \r\n\r\n", для удаления всех пустых строк поле "Заменить на" оставляем пустым и нажимаем кнопку "заменить все".

Замена была произведена 391 раз

## ЧАСТЬ 2.
Для поиска всех князей и городов, имя и название которых оканчивается на "слав" используем регулярное выражение " [А-Я][а-я]*слав"

КАк мы можем видеть на фотографии всего упоминаний о князьях и городах найдено  было 592 раза.


## ЧАСТЬ 3.
Для поиска всех упоминаний Новгорода используем регулярное выражение *"Нов.*?город"
Всего упоминаний о городе Новгород найдено было  59 раз
