# -map-filter-reduce-wm
учебное

Задание 1. Выведите все элементы массива с индексами, которые кратны 3м. Количество элементов массива равно n.

Задание 2. Выведите все четные элементы массива. Количество элементов массива равно n.

Задание 3. Дан массив, состоящий из слов. Замените первую букву каждого слова на заглавную. Вывести результат в виде строки.

Например, a=['В','лесу','родилась','елочка'] -> s="В Лесу Родилась Елочка"

Задание 4. Дана строка. Поменяйте местами первую и последнюю букву каждого слова. Используйте методы split и join. Например, s="В лесу родилась елочка" -> s1= “В уесл ьодиласр алочке”

Задание 5. Сформируйте массив, состоящий из вещественных чисел. Выведите положительные элементы массива на экран. Определите количество положительных элементов массива. Найти произведение отрицательных элементов массива.

Задание 6. В массиве целых чисел определить число инверсий. Инверсией называется пара элементов, в которой большее число расположено слева от меньшего. Например, 24 35 29 44 8 22 4 содержит 3 инверсии.

Задание 7. Разработайте программу, в которой существуют два массива с ростом игроков двух команд (в см). Определить, имеются ли в данных командах игроки одинакового роста.        

Задание 8. Разработайте программу, которая определяет, имеется ли в заданном целочисленном массиве arr(10) хотя бы одна пара совпадающих по значению элементов.

Задание 9. Для данного списка объектов

const students = [

  { name: 'Tirion', class: 'B', mark: 3 },

  { name: 'Keit', class: 'A', mark: 3 },

  { name: 'Ramsey', class: 'A', mark: 4 },

  { name: 'Mike', class: 'B', mark: 5 },

  { name: 'Alex', class: 'C', mark: 2 },

];

Посчитайте средний балл, а также максимальный и минимальный. Посчитайте общую сумму оценок и количество студентов.
Реализуйте функцию для группировки объектов по классу. Функция принимает аргументами массив объектов. Она должна возвращать объект, где ключ - это значение по заданному свойству, а значение - массив с данными, подходящими для группы.
Задание 10.

Реализуйте функцию, которая принимает на вход список сайтов, а возвращает объект, в котором указано количество сайтов, расположенных на каждом домене, если домен передан без указания протокола, то по умолчанию берется http.

const sites = [

    ‘http://google.com’    'https://hexlet.io',    ' yandex.ru',

    'dzen.ru',

    ‘https://ya.ru ',

    'https://github.com',

    'http://mail.ru',

];

Вывод:

// {

//   'http': 4,

//   'https': 3,

// };
