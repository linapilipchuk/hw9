1. Удалить все пустые строки. Использовав регулярное выражение ^\s+ и оставив графу replace with пустой, у меня получилось удалить все пустые строки.
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/пункт%201.1.png)

2. Найти всех князей и города, имя и название которых оканчивается на "слав". Использованное регулярное выражение: [А-ЯѢ]+[а-яѣ]+(слав)[а-яѣ]+, выдало мне 564 вхождения.
![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/кньзья%202.png)

3. Найти все упоминания Новгорода. Данное регулярное выражение позволило мне найти 58 упоминание Новгорода. (Нов)+.(город)[^W]

![alt-текст](https://raw.githubusercontent.com/linapilipchuk/result.txt/master/Новгород%201.png)
