# Задание 1 — обязательное

В этой задаче мы считаем, что пользователь вводит корректные значения входных данных.

Авиаперевозчики предлагают различные бонусные программы, начисляющие бесплатные мили за перелёты. 

*Формула расчёта следующая*: за каждые 20 рублей, потраченные на билет, начисляется 1 миля. Дробные мили не начисляются.

**Нужно создать приложение, рассчитывающее количество начисленных миль за купленный билет.**

Теперь сама логика расчёта будет находиться в специально выделенном классе сервиса, а в Main мы будем лишь создавать объект этого сервиса и вызывать его метод, передавая аргументами все необходимые данные для расчёта. Получив от вызова метода рассчитанный результат, мы выведем его на экран.

**Создайте класс BonusMilesService**

Определите в нём **метод calculate**, который:

принимает на вход один параметр: цену билета, типа int;
анализируя значение переданного параметра, возвращает рассчитанное количество миль.
