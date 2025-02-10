# Алгоритмы и структуры данных

## Описание
Этот проект — моя личная инициатива по реализации алгоритмов, описанных в книге Томаса Кормена *«Алгоритмы. Построение и анализ»*. Основная цель проекта — углубить моё понимание того, как работают различные алгоритмы, их структуры и производительности. Проект не предназначен для практической пользы широкой аудитории, он создан исключительно для моего собственного удовольствия и обучения.

## Эффективность алгоритма
Одно из основных свойств алгоритма - его эффективность. Эффективность алгоритма показывает сколько вычислительных ресурсов потребуется для его выполнения. В наше время (на момент написания данной статьи) это может показаться не таким важным аспектом, так как современные компьютеры имеют огромные мощности, по сравнению с тем, что было 20 лет назад. Но вместе с данными мощностями растут и потребности: данных становится больше, задачи сложнее. Для решения данных задач потребуются ресурсы. И то, насколько эффективно мы можем использовать данные ресурсы, экономит компании огромную кучу денег.<br>
Эффективность алгоритма обеспечивается тем, сколько ресурсов он потребляет. Понять это можно посмотрев на его времнную сложность и пространственную сложность.

**Временная сложность** - это количество времени, которое потребуется алгоритму для выполнения задачи. Чем меньше временная сложность, тем быстрее алгоритм.<br>
**Пространственная сложность** - это объем памяти, который алгоритм будет использовать во время выполнения задачи. Эффективные алгоритмы стараются минимизировать объем потребляемой памяти. 

На самом деле эффективность алгоритма образуют куда больше параметров, но для моих задач этого будет достаточно.

Временная и пространственная сложности выражаются в виде функции от размера входных данных.

|  Обозначение  |        Название         |
| :-----------: | :---------------------: |
|    $O(1)$     |       постоянное        |
|  $O(log(n))$  |     логарифмическое     |
|    $O(n)$     |        линейное         |
| $O(nlog(n))$  | логарифмически линейное |
|   $O(n^2)$    |       квадратное        |
| $O(c^n), c>1$ |    экспоненциальное     |

## Прогресс
Здесь список алгоритмов, которые я изучил и реализовал (данный список будет обновляться по мере моего обучения)

### Sorting Algorithms
- [x] [Insertion Sort](/SortingAlgorithms/insertionSort/README.md)
- [x] [Merge Sort](/SortingAlgorithms/mergeSort/README.md)
- [x] [Selection Sort](/SortingAlgorithms/selectionSort/README.md)
- [x] [Quick Sort](/SortingAlgorithms/quickSort/README.md)
- [ ] Timsort
- [ ] Heap Sort

### Searching Algorithms
- [] Linear Search
- [] Binary Search
- [] Depth-First Search
- [] Breadth-First Search