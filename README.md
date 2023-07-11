﻿## Итоговая проверочная работа.
***Задача***: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначально массив можно вести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
**Пример:**
["Hello", "2", "world", ":-)"] -> ["2", ":-)"] 
["1234", "1567", "-2", "computer science"] -> ["-2"] 
["Russia", "Denmark", "Kazan"] -> [] 

**Алгоритм решения:**

1.Вводится длина массива пользователем;

2. Объявляется массив;

3. Вводится значения каждого элемента массива пользователем;

4. Вводится значения каждого элемента массива пользователем;

5. Вводится значения каждого элемента массива пользователем;

6. Подсчитывается количество элементов массива удовлетворяющие условию задачи для определения длины результирующего массива;

7. Объявляется результирующий массив;

8. Первый объявленный массив обходится циклом, и проверяются значения согласно условию поставленной задачи. Все удовлетворяющие значения заносятся в результирующий массив. Для того чтобы все значения в результирующем массиве вводились по порядку и не вышли за пределы массива, вводится переменная count, которая увеличивается на 1 пункт, если выполняется условие задачи;

9. Выводится результат.

## ***Блок-схема***
![Блок-схема] (blok-shema.png)
