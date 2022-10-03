# Практические задачи, уровень 1/6
Сделал Коршунов Михаил из группы БФИ1801

Список задач для этого уровня



+ ## Напишите функцию, которая принимает целое число минут и преобразует его в секунды. ##

Пример:

```
convert(5) ➞ 300

convert(3) ➞ 180

convert(2) ➞ 120
```

+ ## Вы подсчитываете очки за баскетбольный матч, учитывая количество забитых 2-х и 3-х очков, находите окончательные очки для команды и возвращаете это значение. ##

Пример:
```
points(13, 12) ➞ 62

points(17, 12) ➞ 70

points(38, 8) ➞ 100
```

+ ## Создайте функцию, которая принимает количество побед, ничьих и поражений и вычисляет количество очков, набранных футбольной командой на данный момент. ##


выигрыш – получают 3 очка

ничья – получают 1 очко

проигрыш – получают 0 очков

Пример:
```
footballPoints(3, 4, 2) ➞ 13

footballPoints(5, 0, 2) ➞ 15

footballPoints(0, 0, 1) ➞ 0
```

+ ## Создайте функцию, которая возвращает true, если целое число равномерно делится на 5, и false в противном случае. ##

Пример:
```
divisibleByFive(5) ➞ true

divisibleByFive(-55) ➞ true

divisibleByFive(37) ➞ false
```

+ ##	В Java есть логический оператор &&. Оператор && принимает два логических значения и возвращает true, если оба значения истинны. ##
 
Рассмотрим a && b:

a проверяется, является ли оно истинным или ложным.
Если a равно false, возвращается false.
b проверяется, является ли оно истинным или ложным.
Если b имеет значение false, возвращается значение false.
В противном случае возвращается true (поскольку и a, и b, следовательно, истинны ).
Оператор && вернет true только для true && true.

Создайте функцию с помощью оператора &&.

Пример:
```
and(true, false) ➞ false

and(true, true) ➞ true

and(false, true) ➞ false

and(false, false) ➞ false
```

+ ##	У меня есть ведро с большим количеством темно-синей краски, и я хотел бы покрасить как можно больше стен. Создайте функцию, которая возвращает количество полных стен, которые я могу покрасить, прежде чем мне нужно будет отправиться в магазины, чтобы купить еще. ##

n - это количество квадратных метров, которые я могу нарисовать.

w и h-это ширина и высота одной стены в метрах.

Пример:
```
howManyWalls(54, 1, 43) ➞ 1

howManyWalls(46, 5, 4) ➞ 2

howManyWalls(100, 4, 5) ➞ 5

howManyWalls(10, 15, 12) ➞ 0

howManyWalls(41, 3, 6) ➞ 2
```

Примечание:
- Не считайте стену, если я не успею закончить покраску до того, как у меня закончится краска.
- Все стены будут иметь одинаковые размеры.
- Все числа будут целыми положительными.

+ ##	Исправьте код, чтобы решить эту задачу (только синтаксические ошибки). Посмотрите на приведенные ниже примеры, чтобы получить представление о том, что должна делать эта функция.##

Пример:
```
squared(5) ➞ 25

squared(9) ➞ 81

squared(100) ➞ 10000
```

Код:
```java
public class Challenge {
	public static int squaed(int b) {
		return a * a
  }
}
```


+ ##	Создайте функцию, которая принимает три аргумента prob, prize, pay и возвращает true, если prob * prize > pay; в противном случае возвращает false. ##

Чтобы проиллюстрировать: 

`profitableGamble(0.2, 50, 9)`

... должно давать true, так как чистая прибыль равна 1 (0.2 * 50 - 9), и 1 > 0.

Пример:
```
profitableGamble(0.2, 50, 9) ➞ true

profitableGamble(0.9, 1, 2) ➞ false

profitableGamble(0.9, 3, 2) ➞ true
```

+ ##	Создайте метод, который возвращает количество кадров, показанных за заданное количество минут для определенного FPS.  ##

Пример:
```
frames(1, 1) ➞ 60

frames(10, 1) ➞ 600

frames(10, 25) ➞ 15000
```

+ ##	Создайте функцию, которая будет работать как оператор модуля % без использования оператора модуля. Оператор модуля-это способ определения остатка операции деления. Вместо того чтобы возвращать результат деления, операция по модулю возвращает остаток целого числа.  ##

Пример: 
```
mod(5, 2) ➞ 1

mod(218, 5) ➞ 3

mod(6, 3) ➞ 0
```
