Использовала регулярное выражение: ^\s+ заменила все вхождения на ничего.
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/пункт%201.1.png)

Использовала регулярное выражение: [А-ЯѢ]+[а-яѣ]+(слав)[а-яѣ]+ Всего упоминаний о князьях нашел: 564
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/кньзья%202.png)

Использовала регулярное выражение: (Нов)+.(город)[^W]. Всего упоминаний Новгорода нашел: 58
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/Новгород%201.png)


Бонус!
Сначала я поставила пробелы после всех знаков препинания, использовав регулярное выражение ([.,;:!\?]), а в замене я поставила \1 \2 
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/Б%20Пункт%201.png)

Потом я использовала регулярное выражение (\[) и в замене поставила (пробел)\1, чтобы соблюсти условие "перед квадратной скобкой должен быть пробел"
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/Б%20Пункт%20%5B.png)

Дальше я использовала выражение (\.\s\.\s\.\s) и в замене оставила ..., чтобы соблюсти условие "а после нее (точки) нет другой точки"
![alt-текст])(https://raw.githubusercontent.com/linapilipchuk/result.txt/master/Б%20Пункт%20....png)

Вконце, я заменила все двойный пробелы на один пробел с помощью регулярного вырежения \s\s и в замене поставила один пробел. 
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/%20Б%20Пункт%20пробелы.png)
