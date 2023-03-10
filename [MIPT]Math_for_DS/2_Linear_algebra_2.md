## Задачи

### **1. Линейная независимость**

Для каждого набора векторов укажите, какое наибольшее количество линейно независимых можно выбрать среди данных. Ответ запишите в виде 1,2

1) (2,1),(1,4),(3,2)

2) (4,3,1),(1,2,3),(3,−1,−5)

**Решение**

Ответ: достаточно 2 векторов в базисе для описания векторов размерности 2, аналогично для размерности 3

### **2. Линейная комбинация**

Представьте вектор u как линейную комбинацию векторов v1,v2,v3.

1) u=(3,5), v1=(1,1), v2=(2,3)

2) u=(3,5,1), v1=(1,1,1), v2=(2,3,4), v3=(0,0,1)

Ответ укажите в формате 1,1,2,2,2

**Решение**

1) 

Представим вектор u как линейную комбинацию: (3,5) = a * (1,1) + b * (2,3)

Получаем следующую систему уравнений

3 = a + 2b

5= a + 3b

a = 3 - 2b  ⇒ 5 = 3 - 2b + 3b  ⇒  b = 2

a = 3 - 4 = -1

(3,5) = -1 * (1,1) + 2 * (2,3)

2)

Представим вектор u как линейную комбинацию: (3,5,1) = a * (1,1,1) + b * (2,3,4) + c * (0,0,1)

Получаем следующую систему уравнений

3 = a + 2b 

5 = a + 3b

1 = a + 4b + c

a = 3 - 2b  ⇒ 5 = 3 - 2b + 3b  ⇒  b = 2

a = 3 - 4 = -1

c = 1 - a - 4b = 1 + 1 - 8 =-6

(3,5,1) = -1 * (1,1,1) + 2 * (2,3,4) + -6 * (0,0,1)

Ответ: 1,2,-1,2,-6

### **3. Базис**

Дан базис из векторов (4,1,−1),(1,2,−5),(−1,1,1). Найдите в этом базисе координаты следующих векторов:

1) (4,4,−5);

2) (2,4,−10);

Ответ дайте в формате 1,1,1,2,2,2

**Решение**

1)

(4,4,−5) = a * (4,1,−1) + b * (1,2,−5) + c * (−1,1,1)

Получим систему из 3 уравнений

4 = 4a + b - c

4 = a +2b + c

-5 = -a -5b + c

Будем решать систему методом Гаусса. Сложим второе и третье уравнение и запишем результат как третье. Домножим второе уравнение на -4

4 = 4a + b - c

-16 = -4a -8b -4c

-1 = -3b +2c

Сложим первое и второе уравнение и результат запишем во второе

4 = 4a + b - c

-12 =-7b - 5c

-1 = -3b +2c

Выразим с:   с= (-1+3b) / 2

-12 = -7b - 5(-1+3b) / 2  ⇒  -12 = -7b + 2.5 - 7.5b  ⇒  -14.5 = -14.5b ⇒  b = 1

c = (-1 + 3) / 2 = 1

a = (4 - b + c) / 4 = 1

Таким образом:

(4,4,−5) = (4,1,−1) + (1,2,−5) +(−1,1,1)

2)

Заметим, что (2,4,−10) = 2 * (1,2,−5)

Ответ: 1,1,1,0,2,0

### **4. Линейные пространства**

Какие из следующих множества являются **линейными** пространствами. В ответе укажите строку из 0 и 1 (без пробелов и прочих разделительных символов), где 0 соответствует тому, что множество не линейное пространство, а 1 означает, что это линейное пространство.

1) Множество векторов, первая координата которых равна 0.

2) Множество векторов, сумма координат которых равна 1.

3) Множество векторов плоскости, длина которых не превосходит 1.

4) Множество векторов, параллельных некоторой фиксированной прямой. (точку считаем параллельной любой прямой)

Решение:

1) Все аксиомы выполняются

2) При сложении двух любых векторов получается вектор с суммой равной 2, что не соответствует условию сумма=1, то есть результатом линейной операции получается вектор другого пространства

3) Аналогично предыдущему

4) Все аксиомы выполняются 

### **5. Система линейных уравнений**

Решите систему линейных уравнений.

1) 
2x+3y=13

4x+y=11

2)
x + y + z = 7

4x + 2y + z = 13

-x + 5y + 2z = 8

1) Решаем систему методом Гаусса

Домножим первое уравнение на 2

4x+6y=26

4x+y=11

Вычтим из первого второе

5y=15

4x+y=11

Определим x, y

y = 3

x = (11 - 3) / 4 = 2

2) Решаем систему методом Гаусса

Домножим первое и третье уравнение на -4 и 4

-4x - 4y - 4z = -28

4x + 2y + z = 13

-4x + 20y + 8z = 32

Прибавим к первому и третьему уравнениям второе

-2y - 3z = -15

4x + 2y + z = 13

22y + 9z = 45

Домножим первое уравнение на 11

-22y - 33z = -165

4x + 2y + z = 13

22y + 9z = 45

Сложим первое с третьим

- 24z = -120

4x + 2y + z = 13

22y + 9z = 32

Выразим x, y, z

z = 5, y = 0, x = 2

Ответ: 2,3,2,0,5
