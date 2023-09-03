# Описание проекта:
Имеется некая система, которая обрабатывает авиаперелёты. Перелёт — это перевозка пассажира из одной точки в другую с возможными промежуточными посадками. Т. о. перелёт можно представить как набор из одного или нескольких элементарных перемещений, называемых сегментами. Сегмент — это атомарная перевозка, которую для простоты будем характеризовать всего двумя атрибутами: дата/время вылета и дата/время прилёта.
### Задача:

Вам нужно написать небольшой модуль, который будет заниматься фильтрацией набора перелётов согласно различным правилам. Правил фильтрации может быть очень много. Также наборы перелётов могут быть очень большими. Правила могут выбираться и задаваться динамически в зависимости от контекста выполнения операции фильтрации.

1. Вылет до текущего момента времени
2. Имеются сегменты с датой прилёта раньше даты вылета
3. Общее время, проведённое на земле превышает два часа (время на земле — это интервал между прилётом одного сегмента и вылетом следующего за ним)

### Работаем с:

   - Java 11

   - Maven

