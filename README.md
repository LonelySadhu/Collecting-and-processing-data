## Collecting-and-processing-data
### Methods of collecting and processing data from the Internet

### avia_tickets.py

Данный скрипт запускается из командной строки с ключами -o (город отправления русским алфавитом), -d (город назначения русским алфавитом),
-t (дата в формате yyyy-mm-dd). Возвращает цены на имющиеся авиабилеты на данную дату и компании где можно их приобрести.
пример запуска скрипта  
python avia_tickets.py -o "Москва" -d "Нью-Йорк" -t "2019-07-30"


### article_parsing.py

Данный скрипт принимает аргумент с названием статьи на википедии, считает количество текстовых ссылок в статье,
переходит по второй ссылке и считает 10 наиболее частых слов на странице и выводит их.
