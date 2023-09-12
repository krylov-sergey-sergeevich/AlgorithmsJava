# Алгоритмы и Задачи на Java

## Теория

**Жадный алгоритм**

1. Код Хаффмана

**Деревья**

1. Двоичное дерево поиска (BST)
    - добавление и удаление реализовано просто и сложность достигает O(n)
        - требуется доработка для поддержки сбалансированного состояния
    - другие операции O(log(n))
2. todo

## Практика

### Задачи из книжек / курсов

**Описание задач:** [задачи](docs/tasks/Задачи.md)

**Жадный алгоритм**

1. Задача на монеты
2. Задача про непересекающиеся сегменты
    - Добавлен перебор + стресс тест

### Leetcode

|    №     |                        Название                        | Сложность |      Дата      |                      Заметки                       |       Теги        |
|:--------:|:------------------------------------------------------:|:---------:|:--------------:|:--------------------------------------------------:|:-----------------:|
|  **94**  |             Binary Tree Inorder Traversal              |   Easy    | [[2023-09-12]] |        Проход BinSearch в обратном порядке         |     BinSearch     |
|          |                                                        |           |                |                                                    |                   |
|          |                                                        |           |                |                                                    |                   |
| **377**  |                   Combination Sum IV                   |  Medium   |  [[09.09.23]]  |  Собрать число N используя монетки (перестановка)  |        DP         |
|          |                                                        |           |                |                                                    |                   |
| **1282** |  Group the People Given the Group Size They Belong To  |  Medium   | [[2023-09-11]] | просто разложение по hashMap с учетом переполнения |      HashMap      |
|          |                                                        |           |                |                                                    |                   |
| **1351** |       Count Negative Numbers in a Sorted Matrix        |   Easy    | [[2023-09-12]] |       Или пройтись по матрице или bin search       | Matrix, BinSearch |
| **1359** |      Count All Valid Pickup and Delivery Options       |   Hard    | [[2023-09-10]] |      Правильная скобочная последовательность       |     DP, Math      |
| **1647** | Minimum Deletions to Make Character Frequencies Unique |  Medium   | [[2023-09-12]] | Распределить равные числа чтобы не было совпадений |      TreeSet      |
|          |                                                        |           |                |                                                    |                   |
|          |                                                        |           |                |                                                    |                   |

### Задачи Codeforces

**Жадный алгоритм**

1. https://codeforces.com/problemset/problem/231/A
2. https://codeforces.com/problemset/problem/50/A
3. https://codeforces.com/problemset/problem/339/A  - неплохо с строками работается