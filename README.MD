# transform_file (2024.05.16:1.0.0)
Простенький конвертор изображений

## Что умеет трансформер файла от [by_artisan]:

* [x] Перебирает перебирает все строки в файле в формате {значение}:{дата}
* [x] Сортирует все значения по датам
* [x] Записывает значения в строку, заключая их в двойные ковычки и разделяя запятой
* [x] Для удобства, записывает значения в пачки по n штук (по умолчанию 1000)
* [x] Создаёт новый файл с отсортированнымизначениями

## Также программа понимает следующие команды:
* --version -v    Вывести версию программы
* --param -p      Изменить параметры по умолчанию

### Если --param(-p) указан в командах, можно изменить свойства по умолчанию
* fileInPath (fip)           Название файла с данными               (fileIn.txt)
* fileOutPath (fop)          Название файла вывода                  (fileOut.txt)
* patternData (pd)           Паттерн даты в формате golang          (02.01.2006 15:04:05)
* sep (s)                    Делитель строки                        (;)
* countOrders (co)           Количество значений в одной строке     (1000)

Формат записи -p fileInPath:file.txt s:,
 
### Спасибо, что воспользовались transform_file от [by_artisan]
