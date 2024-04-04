# calc-trig
Поддерживаются базовые арифметические и тригонометрические операции, и ввод десятичных чисел. Операции производятся над значением из единственного регистра (он же - приёмник результата) и, если операция бинарная, вторым операндом, вводимым после оператора. Размер вводимых чисел ограничен 10 десятичными цифрами.

## Пользовательский интерфейс
Пользовательский ввод построчно читается из стандартного ввода, в каждой строке ожидается одна операция или ввод числа (без знака):
```
op [arg]

number
```
Результат каждой операции выводится в стандартный вывод, сообщения об ошибках - в стандартный вывод ошибок.

## Операции
* сложение `+`
* вычитание `-`
* умножение `*`
* деление `/`
* остаток от деления `%`
* инвертирование знака `_`
* возведение в степень `^`
* квадратный корень `SQRT`
* синусу `SIN`
* косинус `COS`
* тангенс `TAN`
* катангенс `CTN`
* арксинус `ASIN`
* арккосинус `ACOS`
* арктангенс `ATAN`
* арккотангенс `ACTN`
* режим радианов `RAD`
* режим градусов `DEG`
