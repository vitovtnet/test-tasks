Надо написать SQL запрос, по которому из таблицы auto_history (x, y, auto) будут выбраны только те автомобили, которые в любой момент времени находились в одной точке с какими-нибудь другими автомобилями.
 
Контрольная таблица:
```
x              y              auto
--------------------
1              2              A
5              3              B
4              6              C
1              2              D
7              7              E
4              6              F
5              3              B
9              4              H
4              6              F
```
 
Контрольный результат:
```
x              y              auto
--------------------
1              2              A
1              2              D
4              6              C
4              6              F
```

Необходимо предоставить дамп таблицы и SQL запрос.
