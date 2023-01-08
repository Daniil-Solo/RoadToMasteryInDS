## Задачи по множествам

### 1. **Мощность пересечение и объединения**

Множество A состоит из 30 элементов, а множество B из 40.

1) Какое максимальное количество элементов в их пересечении max|A∩B|

2) Какое минимальное количество элементов в их пересечении min|A∩B|

3) Какое максимальное количество элементов в их объединении max|A∪B|

4) Какое минимальное количество элементов в их объединении min|A∪B|

В ответ укажите 4 числа через пробел

Ответ: 30 0 70 40

### 2. **Разность множеств**

A∖B - элементы множества A, которые не принадлежат множеству B.

A△B - элементы которые принадлежат ровно одному из множеств A или B.

Пусть A и B это 70 элементные множества из чисел от 1 до 100.

1) Какое минимальное значение |A∖B|

2) Какое максимальное значение |A∖B|

3) Какое максимальное значение |A△B|

В ответ укажите 3 числа через пробел

Ответ: 0 30 60

### 3. **Произведение множеств**

Произведением множеств A×B называется множество пар, где первым элемент это элемент множества А, а второй это элемент множества B.

A×B={(a,b) | a∈A,b∈B}

A^n=A×A×⋯×A

Пусть A состоит из 5 элементов, а B из 10. Найдите мощность A×B и A^5.

Ответ: 50 5^5

### **4. Функции**

Сколько существует функций f из множества A={1,2,3,4,5} в множество B={1,2,…,10}?

Ответ: 10^5

### **5. Тождества с операциями**

Отметьте верные утверждения:

1) A△B=(A∖B)∪(B∖A)

2) A×(B∪C)=A×B∪A×C

3) (A∩B)∪(A∪B)=A∪B

4) (A∩B)∩C=A∩(B∩C)

В ответ укажите 4 числа через пробел. 1 если утверждение верное, 0 если ложное

Ответ: 1 1 1 1

### **6. Утверждения про вложения**

Отметьте верные утверждения:

1) если a∈B и B∈C, то a∈C;

2) если a∈B и B⊂C, то a∈C;

3) если a⊂B и B∈C то a∈C.

В ответ укажите 3 числа через пробел. 1 если утверждение верное, 0 если ложное

Ответ: 0 1 0

### **7. Композиция функций**

Пусть функция f:A→A, где A={1,2,3,4,5,6,7}. 

И f(1)=5, f(2)=3, f(3)=4 ,f(4)=2, f(5)=7, f(6)=1, f(7)=6. Какое минимальное n нужно взять, чтобы f^n(x)=x для всех x∈A, f^n(x)=f(f(…(f))).

Ответ: 12

Пояснение: для 2, 3, 4 необходимо n=k*3, k = {1, 2, …}. Для 1, 5, 6, 7 достаточно n=k*4, k ={1, 2..}. Чтобы композиция функции позволяла получить x→ x, необходимо, чтобы n = k1*3 = k2*4. Минимальное n таким образом равно 12=4*3

## Задачи по логике

### **1. Логические формулы**

Найдите значение формул при p=0,q=1,r=0,t=0

1) (p∨q)∧(r∨t) = 1∧0=0

2) ((p→q)→r)→t=((¬p∨q)→r)→t=(0∨r)→t=1∨t=1

3) (¬p∧q)∨¬(r∨¬t)=1∨¬(0∨1)=1

4)¬(p→p∧q)→(q∨r)=(p→p∧q)∨1=(1∨0)∨1=1

В ответ запишите 4 числа через пробел, 1 если соответствующее выражение истинно и 0 если ложно.

Ответ: 0 1 1 1

### **2. Булева формула**

Постройте таблицу истинности для формул. ∧ - операция И, ∨ - операция ИЛИ, ⊕ - операция XOR (истинна когда ровно один из двух аргументов истинен).

1) p∧q∧r=

2) p∨q∨r

3) p⊕q⊕r

В ответ укажите 3 числа через пробел, количество наборов переменных, при которых соответствующая формула дает значение Истина.

Ответ: 1 7 4

### **3. Кванторы 1**

Отметьте верные утверждения. 1 если утверждение верно, 0 если нет

1) ∀x∈R x^2+1>0

2) ∀x∈R x^2>0

3) ∃x,y,z∈Z x^2+y^2=z^2

4) ∃x,y,z∈Z x^3+y^3=z^3

5) ∀двух точек на плоскости ∃ прямая проходящая через них

6) ∀двух прямых на плоскости ∃ точка лежащая на обоих этих прямых

Ответ: 1 0 1 1 1 0

### **4. Кванторы 2**

Отметьте верные утверждения

1) Функции f,g: A→B равны означает, что ∀x∈A f(x)=g(x)

2) Следующие утверждения означают одно и то же:

∀x∃y Объект x нравится мне не меньше, чем объект y

∃x∀y Объект x нравится мне не меньше, чем объект y

3) Из утверждения

∃x∀y Объект x нравится мне не меньше, чем объект y

следует утверждение

∀x∃y Объект x нравится мне не меньше, чем объект y

4) Из утверждения

∃x∀y Объект y нравится мне не меньше, чем объект x

следует утверждение

∀x∃y Объект x нравится мне не меньше, чем объект y

Ответ: 1 0 0 1

### 6. Рыцари и лжецы

Все жители острова либо рыцари и говорят только правду, либо лжецы и всегда лгут. Путешественник встретил пятерых островитян. На его вопрос: "Сколько среди вас рыцарей?" первый ответил: "Ни одного!", а двое других ответили: "Один". Что ответили остальные?

В ответ напишите два числа через пробел в порядке возрастания.

Рассуждения:

Если первый был рыцарем, то рыцарей нет, что является противоречием. Значит первый лжец.

Два других не могут быть рыцарями одновременно, потому что рыцарей тогда было бы хотя бы 2. Либо они оба лгут, либо лжет только один.

Если лгут оба, то уже 3 лжеца, а значит оставшиеся два должны быть рыцарями, так как ни 1 ни 0 не могут быть правдой.

Если лжет один, а другой говорит правду, то он единственный рыцарь, а значит лжец не соврал, что является противоречием.

Ответ: 2 2

### 7. Математики в тюрьме

Двух математиков посадили в тюрьму и сообщили одному из них натуральное число n, а другому число n+1, при этом математики не знают кому сообщили меньшее, а кому большее.

Математики сидят в разных камерах и не могут общаться между собой, каждый день к каждому из них одновременно приходят охранники и спрашивают "Какое число мы сообщили другому математику?". Если математик отвечает правильно, то обоих отпускают, если отвечает неверно, то обоих казнят, если ничего не отвечает, то процедура продолжается на следующий день.

Математики никак не могут общаться между собой и они не успели договориться о каком-либо кооперативном поведении. Они хотят выбраться из тюрьмы как можно раньше, при этом не готовы никаким образом рисковать своими жизнями.

Как математикам выбраться из тюрьмы и на какой день они это сделают? В ответ напишите ответ для n=1000.

Рассуждения:

Наступает k-ый день. Если для какого-то математика его число n равно k, то он может смело говорить, что у другого k+1, так как иначе он бы уже сам это сказал в предыдущый день. Таким образом, к 1000-ому дню математики смогу освободиться. 

Ответ: 1000