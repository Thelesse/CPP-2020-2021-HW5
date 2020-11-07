# CppSource

Repo for fifth homework on 2019/2020 C++ course

[!] Все реализованные функции надо вынести в отдельные файлы и правильно подключить к основному **main**.

# Task 1

Написать функцию для поиска минимального элемента массива со следующей сигнатурой:

```cpp 
int minElement (int* array, int size); // m - указатель на массив, size - размер массива
```

Пример: 
[1,2,3,4,5] => 1

# Task 2

Написать функцию для поиска минимального элемента массива со следующей сигнатурой:

```cpp 
int minElement (int* first_elem, int* last_elem); // first - указатель на первый элемент массива, last - указатель на последний элемент массива
```

Пример: 
[1,2,3,4,5] => 1

# Task 3

Написать функцию для "переворачивания массива" со следующей сигнатурой:

```cpp 
void rotate (int* first_elem, int* last_elem); // first - указатель на первый элемент массива, last - указатель на последний элемент массива
```

Пример: 
[1,2,3,4,5] => [5,4,3,2,1]
