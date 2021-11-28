**Примерный план занятия:**

1. Начальный вариант
2. Увеличение объёма, потребление оперативной памяти
3. Выделить функцию подсчёта (возможно увеличение потребления памяти)
4. Переделать функцию подсчёта на итератор
5. Переделать функцию генерации на итератор

*Самостоятельно:*
1. Реализовать другую функцию подсчёта, например, "максимальное число среди тех, что делятся на 9"
2. Тест-кейс для этой функции, принимающий массив, зашитый в код

*Домашнее задание:*
1. Попробовать сделать функцию, которая читает из файла и возвращает объект итератора, который можно пихнуть в нашу функцию подсчёта sum_up.
2. Сделать так, чтобы при передаче вектора в sum_up вектор не тратился, и можно было бы, например, вызвать её дважды для одного и того же вектора (избавиться от into_iter). Возможно, придётся изменить тип параметра sum_up (будет ссылка на итератор или не знаю что).
