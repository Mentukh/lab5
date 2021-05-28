# Лабораторна робота №5
## Тема: _Визначення максимального потоку_
## Мета роботи: _Навчитись знаходити максимальний потік між парою вузлів та визначати мінімальний переріз._

## Хід роботи

1. За допомогою лабораторного макету побудувати випадковий неорієнтований зважений граф `G={8,10}`.

![alt text](https://github.com/Mentukh/lab5/blob/main/graph.jpg "Graf")

3. Знайти шлях (вказати послідовність ребер) з максимальною пропускною здатністю (вказати якою) між вузлами `i` та `j` (`i` - вершина витоку (початкова); `j` - вершина стоку (кінцева)). 

![alt text](#URL "Task1")

5. Визначити максимальний потік, який може бути переданий між вузлами `i` та `j`.

        5

7. Вказати ребра, які входять у мінімальний переріз (Переріз - видаляємо ребра графа так щоб не було шляхів між витоком і стоком).

        4-5=4
        5-6=7 

9. Визначити максимальний потік, який може виходити з вузла `i`. Визначити максимальний потік, який може входити у вузол `j`.

        і=15
        j=12

11. Вважаючи, що між вузлами `i` та `j` передається максимальний потік, до яких вузлів можна здійснити передачу інформації з вузла `і`. Визначити пропускну здатність даних маршрутів.

        0-4 = 6
        0-7 = 1
        0-1 = 3 

13. Вважаючи, що між вузлами `i` та `j` передається максимальний потік, які вузли можуть здійснити передачу інформації до вузла `j`. Визначити пропускну здатність даних маршрутів.

        Таких вузлів немає

## Висновок
      В процесі виконання лабораторної роботи було вивчено поняття максимального потоку, створений граф, в якому вихначений максимальний потік.
