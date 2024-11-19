Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина
которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры,
либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться
коллекциями, лучше обойтись исключительно массивами

Действия:
Сначала создаются два массива: один исходный и второй, имеющий такую же длину. Затем запускается метод, содержащий цикл, который соответствует 
длине массива. Внутри этого цикла проверяется условие (<=3). Если условие выполняется, элемент из первого массива записывается в позицию count
второго массива. Переменная count используется для последовательного добавления элементов из первого массива во второй, чтобы избежать пробелов. 
После записи значение переменной count увеличивается на 1, возвращамся в цикл for, где индекс i инкрементируется на 1. Этот процесс 
продолжается до завершения цикла.
