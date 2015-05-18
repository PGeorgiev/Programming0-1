# Второто най-голямо число.

**Файлът трябва да се казва `second.py`**

Всеки от нас може да напише функция, която намира най-голямото число в списък.

Сега е ред да намерим второто най-голямо такова!

Напишете следната функция:

```python
def second_largest(numbers):
    pass
```

Важно е да спазим следните изисквания:

* Второто най-голямо число трябва да има различна стойност от първото.
* Ако списъкът е с по-малко от 2 елемента или пък няма второ най-голямото такова число, върнете `False`

Примери:

```python
>>> second_largest([])
False
>>> second_largest([2, 1])
1
>>> second_largest([5, 5])
False
>>> second_largest([100, 100, 90])
90
```