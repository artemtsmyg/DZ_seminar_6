# Задача 30:  Заполните массив элементами арифметической прогрессии. 
# Её первый элемент, разность и количество элементов нужно ввести с клавиатуры. 
# Формула для получения n-го члена прогрессии: an = a1 + (n-1) * d.
# Каждое число вводится с новой строки.

a1 = int(input("Введите первый элемент массива: "))
d = int(input("Введите разность элементов массива: "))
n = int(input("Введите количество элементов массива: "))

for i in range(n):
      print(a1 + i * d)
   
   






# Задача 32: Определить индексы элементов массива (списка), значения которых принадлежат заданному диапазону
# (т.е. не меньше заданного минимума и не больше заданного максимума)

max = int(input("Введите максимальное число массива: "))
min = int(input("Введите минимальное число массива: "))
array_1 = [-5, 9, 0, 30, -1, -2, 1, 4, -2, 10, 2, 0, -9, 80, 10, -9, 0, -5, -5, 7]

for i in range(len(array_1)):
    if min <= array_1[i] <= max:
        print(i)
