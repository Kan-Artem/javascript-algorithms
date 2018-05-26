# JavaScript Алгоритмы и Структуры Данных

[![Build Status](https://travis-ci.org/trekhleb/javascript-algorithms.svg?branch=master)](https://travis-ci.org/trekhleb/javascript-algorithms)
[![codecov](https://codecov.io/gh/trekhleb/javascript-algorithms/branch/master/graph/badge.svg)](https://codecov.io/gh/trekhleb/javascript-algorithms)

Этот репозиторий содержит примеры на языке JavaScript многих популярных алгоритмов и структур данных.

Каждый алгоритм и структура данных имеют свой собственный файл README с соответствующими пояснениями и ссылками для дальнейшего чтения и видео на YouTube.

_Read this in other languages:_ 
[_English_](https://github.com/trekhleb/javascript-algorithms/),
[简体中文](https://github.com/trekhleb/javascript-algorithms/blob/master/README.zh-CN.md),
[繁體中文](https://github.com/trekhleb/javascript-algorithms/blob/master/README.zh-TW.md),

## Структура данных

Структура данных — это особый способ организации и хранения данных на компьютере, чтобы обеспечить доступ к ним и их эффективное изменение. Точнее, структура данных представляет собой набор значений данных, взаимосвязь между ними и функции или операции, которые могут применяться к данным.

* [Linked List](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/linked-list)
* [Queue](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/queue)
* [Stack](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/stack)
* [Hash Table](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/hash-table)
* [Heap](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/heap)
* [Priority Queue](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/priority-queue)
* [Trie](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/trie)
* [Tree](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/tree)
    * [Binary Search Tree](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/tree/binary-search-tree)
    * [AVL Tree](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/tree/avl-tree)
    * Red-Black Tree
    * Suffix Tree
    * Segment Tree or Interval Tree
    * Binary Indexed Tree or Fenwick Tree
* [Graph](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/graph) (как направленные, так и неориентированные)
* [Disjoint Set](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/disjoint-set)

## Алгоритмы

Алгоритм - это однозначная спецификация того, как решить класс проблем. Алгоритм - это набор правил, который точно определяет последовательность операций.

### Алгоритмы по Темам

* **Математика**
  * [Factorial](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/factorial)
  * [Fibonacci Number](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/fibonacci)
  * [Primality Test](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/primality-test) (метод пробного деления)
  * [Euclidean Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/euclidean-algorithm) - вычистение Наибольшего Общего Делителя (НОД)
  * [Least Common Multiple](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/least-common-multiple) (НОК)
  * [Integer Partition](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/integer-partition)
* **Наборы**
  * [Cartesian Product](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/cartesian-product) - произведение множества множеств
  * [Power Set](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/power-set) - все подмножества множества 
  * [Permutations](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/permutations) (с повторениями и без них)
  * [Combinations](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/combinations) (с повторениями и без них)
  * [Fisher–Yates Shuffle](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/fisher-yates) - случайная перестановка конечной последовательности
  * [Longest Common Subsequence](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/longest-common-subsequnce) (Наибольшая общая подпоследовательность) 
  * [Longest Increasing subsequence](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/longest-increasing-subsequence) (Наибольшая увеличивающаяся подпоследовательность)
  * [Shortest Common Supersequence](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/shortest-common-supersequence) (Наимельшая общая подпоследовательность)
  * [Knapsack Problem](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/knapsack-problem) - "0/1" and "Unbound" ones
  * [Maximum Subarray](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/maximum-subarray) - "Варианты "Brute Force" ("Грубая сила") и ("Brute Force") "Динамическое программирование" (Kadane)
* **Строки**
  * [Levenshtein Distance](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/levenshtein-distance) - минимальное расстояние редактирования между двумя последовательностями
  * [Hamming Distance](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/hamming-distance) - number of количество позиций с различными символами
  * [Knuth–Morris–Pratt Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/knuth-morris-pratt) - поиск подстроки
  * [Rabin Karp Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/rabin-karp) - поиск подстроки
  * [Longest Common Substring](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/longest-common-substring)
* **Поиск**
  * [Linear Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/search/linear-search)
  * [Binary Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/search/binary-search)
* **Сортировка**
  * [Bubble Sort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/bubble-sort)
  * [Selection Sort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/selection-sort)
  * [Insertion Sort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/insertion-sort)
  * [Heap Sort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/heap-sort)
  * [Merge Sort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/merge-sort)
  * [Quicksort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/quick-sort)
  * [Shellsort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/shell-sort)
* **Дерево**  
  * [Depth-First Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/tree/depth-first-search) (DFS) - поиск в глубину
  * [Breadth-First Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/tree/breadth-first-search) (BFS) - поиск в ширину
* **График**
  * [Depth-First Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/depth-first-search) (DFS) - поиск в глубину
  * [Breadth-First Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/breadth-first-search) (BFS) - поиск в ширину
  * [Dijkstra Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/dijkstra) - поиск кратчайшего пути ко всем вершинам графа
  * [Bellman-Ford Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/bellman-ford) - поиск кратчайшего пути ко всем вершинам графа
  * [Detect Cycle](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/detect-cycle) - как для направленных, так и неориентированных графиков (версии на основе DFS и Disjoint Set)
  * [Prim’s Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/prim) - поиск минимального связующего дерева (MST) для взвешенного неориентированного графика
  * [Kruskal’s Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/kruskal) - поиск минимального связующего дерева (MST) для взвешенного неориентированного графика
  * [Topological Sorting](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/topological-sorting) - DFS method
  * [Articulation Points](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/articulation-points) - алгоритм Tarjan'а (основанный на DFS)
  * [Bridges](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/bridges) - алгоритм, основанный на DFS
  * [Eulerian Path and Eulerian Circuit](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/eulerian-path) - алгоритм Fleury'а - Посетите каждый край ровно один раз
  * [Hamiltonian Cycle](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/hamiltonian-cycle) - Посетите каждую вершину ровно один раз
  * [Strongly Connected Components](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/strongly-connected-components) - алгоритм Kosaraju'а
  * [Travelling Salesman Problem](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/travelling-salesman) - кратчайший маршрут, который посещает каждый город и возвращается в город происхождения
* **Другое**  
  * [Tower of Hanoi](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/hanoi-tower)
  * [N-Queens Problem](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/n-queens)
  * [Knight's Tour](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/knight-tour)
  
### Алгоритмы по Парадигме

Алгоритмическая парадигма - это общий метод или подход, который лежит в основе разработки класса алгоритмов. Это абстракция выше, чем понятие алгоритма, так же как алгоритм является абстракцией выше компьютерной программы.
* **Brute Force** - посмотрите на все возможности и выберите лучшее решение
  * [Maximum Subarray](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/maximum-subarray)
  * [Travelling Salesman Problem](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/travelling-salesman) - кратчайший маршрут, который посещает каждый город и возвращается в город происхождения
* **Greedy** - выберите лучший вариант в текущее время, без какого-либо учета будущего
  * [Unbound Knapsack Problem](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/knapsack-problem)
  * [Dijkstra Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/dijkstra) -поиск кратчайшего пути ко всем вершинам графа
  * [Prim’s Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/prim) - поиск минимального связующего дерева (MST) для взвешенного неориентированного графика
  * [Kruskal’s Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/kruskal) - поиск минимального связующего дерева (MST) для взвешенного неориентированного графика
* **Divide and Conquer** - разделить проблему на более мелкие части, а затем решить эти части
  * [Binary Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/search/binary-search)
  * [Tower of Hanoi](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/hanoi-tower)
  * [Euclidean Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/euclidean-algorithm) - вычислить Наибольший Общий Делитель (НОД)
  * [Permutations](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/permutations) (с повторениями и без них)
  * [Combinations](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/combinations) (с повторениями и без них)
  * [Merge Sort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/merge-sort)
  * [Quicksort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/quick-sort)
  * [Tree Depth-First Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/tree/depth-first-search) (DFS)
  * [Graph Depth-First Search](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/depth-first-search) (DFS)
* **Dynamic Programming** - создавать до решения, используя ранее найденные подрешения
  * [Fibonacci Number](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/fibonacci)
  * [Levenshtein Distance](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/levenshtein-distance) - минимальное расстояние редактирования между двумя последовательностями
  * [Longest Common Subsequence](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/longest-common-subsequnce) (LCS)
  * [Longest Common Substring](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/longest-common-substring)
  * [Longest Increasing subsequence](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/longest-increasing-subsequence)
  * [Shortest Common Supersequence](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/shortest-common-supersequence)
  * [0/1 Knapsack Problem](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/knapsack-problem)
  * [Integer Partition](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/integer-partition)
  * [Maximum Subarray](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/maximum-subarray)
  * [Bellman-Ford Algorithm](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/bellman-ford) - поиск кратчайшего пути ко всем вершинам графа
* **Backtracking** - аналогично грубой силе, пытаться сгенерировать все возможные решения, но каждый раз, когда вы генерируете тест решения, если он удовлетворяет всем условиям, и только затем продолжать генерировать последующие решения. В противном случае отступите назад и идите по другому пути поиска решения.
  * [Hamiltonian Cycle](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/hamiltonian-cycle) - Посетите каждую вершину ровно один раз
  * [N-Queens Problem](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/n-queens)
  * [Knight's Tour](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/knight-tour)
* **Отрасль & граница**

## Как использовать этот репозиторий

**Установка всех зависимостей**
```
npm install
```

**Запуск всех тестов**
```
npm test
```

**Запуск тестов по названию**
```
npm test -- -t 'LinkedList'
```

**Playground**

Вы можете играть с структурами данных и алгоритмами в файле ./src/playground/playground.js и записывать тесты для него в ./src/playground/__test__/playground.test.js.

Затем просто выполните следующую команду, чтобы проверить, работает ли ваш playground код как ожидалось:

```
npm test -- -t 'playground'
```

## Полезная информация


### Рекомендации

[▶ Структура Данных и Алгоритмы на YouTube](https://www.youtube.com/playlist?list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

### Big O Нотация
    
Порядок роста алгоритмов, указанных в нотации Big O.
    
![Big O graphs](https://github.com/trekhleb/javascript-algorithms/blob/master/assets/big-o-graph.png?raw=true)

Источник: [Big O Cheat Sheet](http://bigocheatsheet.com/).
    
Ниже приведен список некоторых из наиболее используемых нот Big O и их сравнение производительности с различными размерами входных данных.

| Big O Notation | Вычисления для 10 элементов  | Вычисления для 100 элементов  | Вычисления для 1000 элементов   |
| -------------- | ---------------------------- | ----------------------------- | ------------------------------- |
| **O(1)**       | 1                            | 1                             | 1                               |
| **O(log N)**   | 3                            | 6                             | 9                               |
| **O(N)**       | 10                           | 100                           | 1000                            |
| **O(N log N)** | 30                           | 600                           | 9000                            |
| **O(N^2)**     | 100                          | 10000                         | 1000000                         |
| **O(2^N)**     | 1024                         | 1.26e+29                      | 1.07e+301                       |
| **O(N!)**      | 3628800                      | 9.3e+157                      | 4.02e+2567                      |

### Сложность Операций с Структурой Данных
        
| Data Structure          | Access    | Search    | Insertion | Deletion  | Comments  |
| ----------------------- | :-------: | :-------: | :-------: | :-------: | :-------- | 
| **Array**               | 1         | n         | n         | n         |           |
| **Stack**               | n         | n         | 1         | 1         |           |
| **Queue**               | n         | n         | 1         | 1         |           | 
| **Linked List**         | n         | n         | 1         | 1         |           |
| **Hash Table**          | -         | n         | n         | n         | В случае идеальной стоимости функции хеш-функции O (1) |
| **Binary Search Tree**  | n         | n         | n         | n         | В случае сбалансированных затрат на дерево будет O (log (n)) |
| **B-Tree**              | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Red-Black Tree**      | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **AVL Tree**            | log(n)    | log(n)    | log(n)    | log(n)    |           |

### Сложность алгоритмов сортировки массивов

| Name                  | Best      | Average   | Worst         | Memory    | Stable    |
| --------------------- | :-------: | :-------: | :-----------: | :-------: | :-------: |
| **Bubble sort**       | n         | n^2       | n^2           | 1         | Yes       |
| **Insertion sort**    | n         | n^2       | n^2           | 1         | Yes       |
| **Selection sort**    | n^2       | n^2       | n^2           | 1         | No        |
| **Heap sort**         | n log(n)  | n log(n)  | n log(n)      | 1         | No        |
| **Merge sort**        | n log(n)  | n log(n)  | n log(n)      | n         | Yes       |
| **Quick sort**        | n log(n)  | n log(n)  | n^2           | log(n)    | No        |
| **Shell sort**        | n log(n)  | depends on gap sequence   | n (log(n))^2  | 1         | No        |
