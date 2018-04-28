# Решатель квадратных уравнений

Реализована функция, вычисляющая корни квадратных уравнений, а так же тесты для проверки работы.

# Как использовать

Необходимо запустить тесты. Запуск описан в разделе "Как запустить".
За расчет отвечает функция get_roots, параметрами которой являются числа a, b и с.
Названия параметров соответствуют названиям коэффициентов квадратного уравнения. 

```python
>>>import quadratic_equation
>>>root1, root2 = quadratic_equation.get_roots(4, 8, 3)
>>>print ("Квадратное уравнение имеет корни %f, %f" % (root1, root2))
Квадратное уравнение имеет корни -1.500000, -0.500000
```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
