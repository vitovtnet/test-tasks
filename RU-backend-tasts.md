
# Aventus Group 

Тестовые задания / Backend

Для всех заданий фиксируйте время, которой понадобилось для решения. 

### Задание 1. Немного логики. 

Дается случайный текст в файле (файл следует приложить к заданию, содержание не имеет значения, кодировка - UTF-8). PHP скрипт должен прочитать текст и заменить каждое слово в тексте, позиция которого делится без остатка на 3 - словом -ТРИ-, каждое слово, позиция которого делится без остатка на 5 - словом -ПЯТЬ-, а если позиция слова делится без остатка и на 3 и на 5 - заменить его словом -ПЯТНАДЦАТЬ-. После обработки текста - результат сохранить в новом файле.

### Задание 2. Дебаг. 

Дана программа [file_manager.php](https://github.com/vitovtnet/test-tasks/blob/master/file_manager.zip) которая работает как файл - менеджер (показывает, какие файлы и каталоги находятся в одной директории с программой). Однако, по неизвестным причинам, скрипт в файле file_manager.php начинает очень сильно тормозить при большом количестве файлов (больше 20). Необходимо определить, какая функция работает медленно, и точно указать, что же так негативно влияет на время работы программы. 
Объясните, как было найдено решение.   

### Задание 3. Предметная область. 
Написать скрипт кредитного калькулятора используя PHP и Javascript (можно но не обязательно использовать React \ Angular \ Vue) , оформление - Bootstrap.

В задаче необходимо реализовать:  


Клиент вводит сумму кредита, указывает срок кредита в месяцах и процентную ставку, дату первого платежа. Скрипт выводит таблицу с графиком платежей в формате: № платежа, Дата платежа, Основной долг, проценты, общая сумма, остаток долга
Вид платежа - аннуитетный. 
Расчет происходит на стороне Backend все данные отправляются AJAX запросами.
История подсчетов и график платежей сохраняются в MySQL для последующего анализа.

Для реализации back-end необходимо использовать Symfony 

=====

Исходный код выложите на github / bitbucket

