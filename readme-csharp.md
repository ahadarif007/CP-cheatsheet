### C# cheatsheet for Interview Coding Problems / Competitive Programming

---

## Table of Contents

| Section                                        | Description                                |
|------------------------------------------------|--------------------------------------------|
| [1. Language Mechanics](#1-language-mechanics) | Basics, syntax, built-ins, data structures |
| [2. Collections](#2-collections)               | Common collection patterns                 |
| [3. Algorithms](#3-algorithms)                 | Common interview patterns                  |

---

## 1. Language Mechanics

|  No. | Topic                                                   | What                                               |
|-----:|---------------------------------------------------------|----------------------------------------------------|
| 1.01 | [Literals](csharp/1.01-literals.md)                     | Number, string, boolean, and null literal forms.   |
| 1.02 | [Loops](csharp/1.02-loops.md)                           | `for`/`while`/`foreach` patterns and loop control. |
| 1.03 | [Strings](csharp/1.03-strings.md)                       | Common string operations and interview tricks.     |
| 1.04 | [Slicing](csharp/1.04-slicing.md)                       | Substring and range-based array extraction.        |
| 1.05 | [Tuple](csharp/1.05-tuple.md)                           | Value tuples and deconstruction patterns.          |
| 1.06 | [Sort](csharp/1.06-sort.md)                             | Built-in sorting with comparisons and LINQ order.  |
| 1.07 | [Hash](csharp/1.07-hash.md)                             | Dictionary-based lookup and counting.              |
| 1.08 | [Set](csharp/1.08-set.md)                               | Fast membership checks with HashSet.               |
| 1.09 | [List](csharp/1.09-list.md)                             | List operations and common methods.                |
| 1.10 | [Dict](csharp/1.10-dict.md)                             | Key-value operations and counting/grouping idioms. |
| 1.12 | [Binary Tree](csharp/1.12-binary-tree.md)               | Binary tree traversal and recursion templates.     |
| 1.13 | [Graph](csharp/1.13-graph.md)                           | Graph modeling with BFS/DFS foundations.            |
| 1.14 | [PriorityQueue](csharp/1.14-heapq.md)                  | Priority queue operations with PriorityQueue.      |
| 1.15 | [Lambda](csharp/1.15-lambda.md)                         | Lambda expressions for concise transformations.    |
| 1.16 | [Zip](csharp/1.16-zip.md)                               | Parallel iteration with LINQ Zip.                  |
| 1.17 | [Random](csharp/1.17-random.md)                         | Random generation and shuffle basics.              |
| 1.18 | [Constants](csharp/1.18-constants.md)                   | Common constants and practical conventions.         |
| 1.19 | [Ternary](csharp/1.19-ternary.md)                       | Inline conditional expression patterns.            |
| 1.20 | [Bitwise Operators](csharp/1.20-bitwise-operators.md)   | Bit manipulation operators and common tricks.      |
| 1.21 | [For Else](csharp/1.21-for-else.md)                     | Simulating for-else control flow with flags.       |
| 1.22 | [Modulo](csharp/1.22-modulo.md)                         | Mod arithmetic behavior and negative handling.     |
| 1.23 | [Any](csharp/1.23-any.md)                               | LINQ-based truth-testing with `Any()`.             |
| 1.24 | [All](csharp/1.24-all.md)                               | LINQ-based validation with `All()`.                |
| 1.25 | [Bisect](csharp/1.25-bisect.md)                         | Binary search and lower/upper bound templates.     |
| 1.26 | [Math](csharp/1.26-math.md)                             | Useful `Math` utilities for coding problems.       |
| 1.28 | [Iter](csharp/1.28-iter.md)                             | Enumerator protocol and traversal patterns.        |
| 1.29 | [Map](csharp/1.29-map.md)                               | Functional mapping with LINQ Select.               |
| 1.30 | [Filter](csharp/1.30-filter.md)                         | Predicate-based filtering with LINQ Where.         |
| 1.31 | [Reduce](csharp/1.31-reduce.md)                         | Folding sequences with LINQ Aggregate.             |
| 1.33 | [Regular Expression](csharp/1.33-regular-expression.md) | Pattern matching and replacement workflows.        |
| 1.34 | [Types](csharp/1.34-types.md)                           | Generic type declarations and common patterns.     |
| 1.35 | [Grids](csharp/1.35-grids.md)                           | Matrix navigation and 2D indexing patterns.        |

---

## 2. Collections

| No. | Topic                                        | What                                               |
|----:|----------------------------------------------|----------------------------------------------------|
| 2.1 | [Deque](csharp/2.1-deque.md)                 | O(1) operations from both ends with LinkedList.    |
| 2.2 | [Counter](csharp/2.2-counter.md)             | Frequency counting and top-k element patterns.     |
| 2.3 | [Default Dict](csharp/2.3-default-dict.md)   | Auto-initialized dictionary for grouping/counting. |

---

## 3. Algorithms

|  No. | Topic                                                                    | What                                              |
|-----:|--------------------------------------------------------------------------|---------------------------------------------------|
| 3.01 | [General Tips](csharp/3.01-general-tips.md)                              | Practical interview heuristics and coding habits. |
| 3.02 | [Binary Search](csharp/3.02-binary-search.md)                           | Search on sorted/answer space with boundaries.    |
| 3.03 | [Binary Search Tree](csharp/3.03-binary-search-tree.md)                 | BST properties, traversal, and operations.        |
| 3.04 | [Topological Sort](csharp/3.04-topological-sort.md)                     | DAG ordering via indegree or DFS approach.        |
| 3.05 | [Sliding Window](csharp/3.05-sliding-window.md)                         | Subarray/substring optimization with windows.     |
| 3.06 | [Greedy](csharp/3.06-greedy.md)                                         | Local-optimal strategies and proof intuition.     |
| 3.07 | [Tree Tricks](csharp/3.07-tree-tricks.md)                               | Common tree shortcuts and recursion templates.    |
| 3.08 | [Anagrams](csharp/3.08-anagrams.md)                                     | Character-count/hash approaches for anagrams.     |
| 3.09 | [Dynamic Programming](csharp/3.09-dynamic-programming.md)               | State transitions, memoization, and tabulation.   |
| 3.10 | [Cyclic Sort](csharp/3.10-cyclic-sort.md)                               | In-place index placement for constrained arrays.  |
| 3.11 | [Quick Sort](csharp/3.11-quick-sort.md)                                  | Partition-based divide-and-conquer sorting.       |
| 3.12 | [Merge Sort](csharp/3.12-merge-sort.md)                                 | Stable divide-and-conquer sorting framework.      |
| 3.13 | [Merge K Sorted Arrays](csharp/3.13-merge-arrays.md)                    | Heap-based merging across multiple sorted lists.  |
| 3.14 | [Linked List](csharp/3.14-linked-list.md)                               | Pointer techniques for traversal and mutation.    |
| 3.15 | [Convert Base](csharp/3.15-convert-base.md)                             | Base conversion logic and number representation.  |
| 3.16 | [Parenthesis](csharp/3.16-parenthesis.md)                               | Stack-based validation and generation patterns.   |
| 3.17 | [Max Profit Stock](csharp/3.17-max-profit-stock.md)                     | Profit optimization across stock constraints.     |
| 3.18 | [Shift Array Right](csharp/3.18-shift-array-right.md)                   | Rotation techniques with O(1) extra space.        |
| 3.19 | [Continuous Subarrays with Sum k](csharp/3.19-continuous-subarrays.md)   | Prefix sum + hashmap counting approach.           |
| 3.20 | [Events](csharp/3.20-events.md)                                         | Interval scheduling and event-line strategies.    |
| 3.21 | [Merge Meetings](csharp/3.21-merge-meetings.md)                         | Interval merge logic after sorting by start.      |
| 3.22 | [Trie](csharp/3.22-trie.md)                                             | Prefix tree for fast string prefix queries.       |
| 3.23 | [Kadane's Algorithm](csharp/3.23-kadane.md)                             | Maximum subarray in linear time.                  |
| 3.24 | [Union Find / DSU](csharp/3.24-union-find.md)                           | Connectivity tracking with path compression.      |
| 3.25 | [Fast Power](csharp/3.25-fast-power.md)                                 | Exponentiation by squaring in logarithmic time.   |
| 3.26 | [Fibonacci Golden](csharp/3.26-fibonacci-golden.md)                     | Closed-form Fibonacci intuition and caveats.      |
| 3.27 | [Basic Calculator](csharp/3.27-basic-calculator.md)                     | Expression parsing with stack/state handling.     |
| 3.28 | [Reverse Polish](csharp/3.28-reverse-polish.md)                         | Stack evaluation of postfix expressions.          |
| 3.29 | [Reservoir Sampling](csharp/3.29-reservoir-sampling.md)                 | Uniform sampling from unknown-length streams.     |
| 3.30 | [String Subsequence](csharp/3.30-string-subsequence.md)                 | Two-pointer checks and preprocessing methods.     |
| 3.31 | [Candy Crush](csharp/3.31-candy-crush.md)                               | Stack-based consecutive duplicate removal.        |
| 3.32 | [Dutch Flag](csharp/3.32-dutch-flag.md)                                  | Three-way partitioning in one pass.               |
