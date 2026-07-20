### Python3 cheatsheet for Interview Coding Problems / Competitive Programming

---

## Table of Contents

| Section                                        | Description                                |
|------------------------------------------------|--------------------------------------------|
| [1. Language Mechanics](#1-language-mechanics) | Basics, syntax, built-ins, data structures |
| [2. Collections](#2-collections)               | `collections` module essentials            |
| [3. Algorithms](#3-algorithms)                 | Common interview patterns                  |

---

## 1. Language Mechanics

|  No. | Topic                                                   | What                                               |
|-----:|---------------------------------------------------------|----------------------------------------------------|
| 1.01 | [Literals](python/1.01-literals.md)                     | Number, string, boolean, and null literal forms.   |
| 1.02 | [Loops](python/1.02-loops.md)                           | `for`/`while` patterns and loop control usage.     |
| 1.03 | [Strings](python/1.03-strings.md)                       | Common string operations and interview tricks.     |
| 1.04 | [Slicing](python/1.04-slicing.md)                       | Slice syntax for arrays/strings and edge cases.    |
| 1.05 | [Tuple](python/1.05-tuple.md)                           | Immutable sequences and unpacking patterns.        |
| 1.06 | [Sort](python/1.06-sort.md)                             | Built-in sorting with keys and custom order.       |
| 1.07 | [Hash](python/1.07-hash.md)                             | Hashing basics and hash-based lookup usage.        |
| 1.08 | [Set](python/1.08-set.md)                               | Fast membership checks and set operations.         |
| 1.09 | [List](python/1.09-list.md)                             | Dynamic array operations and common methods.       |
| 1.10 | [Dict](python/1.10-dict.md)                             | Key-value operations and counting/grouping idioms. |
| 1.11 | [Tree](python/1.11-tree.md)                             | General tree representation and traversals.        |
| 1.12 | [Binary Tree](python/1.12-binary-tree.md)               | Binary tree traversal and recursion templates.     |
| 1.13 | [Graph](python/1.13-graph.md)                           | Graph modeling with BFS/DFS foundations.           |
| 1.14 | [Heapq](python/1.14-heapq.md)                           | Priority queue operations with `heapq`.            |
| 1.15 | [Lambda](python/1.15-lambda.md)                         | Anonymous functions for concise transformations.   |
| 1.16 | [Zip](python/1.16-zip.md)                               | Parallel iteration and tuple packing/unpacking.    |
| 1.17 | [Random](python/1.17-random.md)                         | Random generation and controlled sampling basics.  |
| 1.18 | [Constants](python/1.18-constants.md)                   | Common constants and practical conventions.        |
| 1.19 | [Ternary](python/1.19-ternary.md)                       | Inline conditional expression patterns.            |
| 1.20 | [Bitwise Operators](python/1.20-bitwise-operators.md)   | Bit manipulation operators and common tricks.      |
| 1.21 | [For Else](python/1.21-for-else.md)                     | `for-else` control flow for search-style loops.    |
| 1.22 | [Modulo](python/1.22-modulo.md)                         | Mod arithmetic behavior and interview use cases.   |
| 1.23 | [Any](python/1.23-any.md)                               | Truth-testing iterable items with `any()`.         |
| 1.24 | [All](python/1.24-all.md)                               | Validating iterable items with `all()`.            |
| 1.25 | [Bisect](python/1.25-bisect.md)                         | Binary insertion/search in sorted arrays.          |
| 1.26 | [Math](python/1.26-math.md)                             | Useful `math` utilities for coding problems.       |
| 1.27 | [eval](python/1.27-eval.md)                             | Expression evaluation basics and caution points.   |
| 1.28 | [Iter](python/1.28-iter.md)                             | Iterator protocol and lazy traversal patterns.     |
| 1.29 | [Map](python/1.29-map.md)                               | Functional mapping across iterables.               |
| 1.30 | [Filter](python/1.30-filter.md)                         | Predicate-based filtering of iterable values.      |
| 1.31 | [Reduce](python/1.31-reduce.md)                         | Folding sequences into single accumulated results. |
| 1.32 | [itertools](python/1.32-itertools.md)                   | Efficient combinatoric and iterator utilities.     |
| 1.33 | [Regular Expression](python/1.33-regular-expression.md) | Pattern matching and extraction workflows.         |
| 1.34 | [Types](python/1.34-types.md)                           | Type checks, conversions, and annotations basics.  |
| 1.35 | [Grids](python/1.35-grids.md)                           | Matrix navigation and 2D indexing patterns.        |

---

## 2. Collections

| No. | Topic                                      | What                                               |
|----:|--------------------------------------------|----------------------------------------------------|
| 2.1 | [Deque](python/2.1-deque.md)               | O(1) pops/appends from both ends.                  |
| 2.2 | [Counter](python/2.2-counter.md)           | Frequency counting and top-k element patterns.     |
| 2.3 | [Default Dict](python/2.3-default-dict.md) | Auto-initialized dictionary for grouping/counting. |

---

## 3. Algorithms

|  No. | Topic                                                                  | What                                              |
|-----:|------------------------------------------------------------------------|---------------------------------------------------|
| 3.01 | [General Tips](python/3.01-general-tips.md)                            | Practical interview heuristics and coding habits. |
| 3.02 | [Binary Search](python/3.02-binary-search.md)                          | Search on sorted/answer space with boundaries.    |
| 3.03 | [Binary Search Tree](python/3.03-binary-search-tree.md)                | BST properties, traversal, and operations.        |
| 3.04 | [Topological Sort](python/3.04-topological-sort.md)                    | DAG ordering via indegree or DFS approach.        |
| 3.05 | [Sliding Window](python/3.05-sliding-window.md)                        | Subarray/substring optimization with windows.     |
| 3.06 | [Greedy](python/3.06-greedy.md)                                        | Local-optimal strategies and proof intuition.     |
| 3.07 | [Tree Tricks](python/3.07-tree-tricks.md)                              | Common tree shortcuts and recursion templates.    |
| 3.08 | [Anagrams](python/3.08-anagrams.md)                                    | Character-count/hash approaches for anagrams.     |
| 3.09 | [Dynamic Programming](python/3.09-dynamic-programming.md)              | State transitions, memoization, and tabulation.   |
| 3.10 | [Cyclic Sort](python/3.10-cyclic-sort.md)                              | In-place index placement for constrained arrays.  |
| 3.11 | [Quick Sort](python/3.11-quick-sort.md)                                | Partition-based divide-and-conquer sorting.       |
| 3.12 | [Merge Sort](python/3.12-merge-sort.md)                                | Stable divide-and-conquer sorting framework.      |
| 3.13 | [Merge K Sorted Arrays](python/3.13-merge-arrays.md)                   | Heap-based merging across multiple sorted lists.  |
| 3.14 | [Linked List](python/3.14-linked-list.md)                              | Pointer techniques for traversal and mutation.    |
| 3.15 | [Convert Base](python/3.15-convert-base.md)                            | Base conversion logic and number representation.  |
| 3.16 | [Parenthesis](python/3.16-parenthesis.md)                              | Stack-based validation and generation patterns.   |
| 3.17 | [Max Profit Stock](python/3.17-max-profit-stock.md)                    | Profit optimization across stock constraints.     |
| 3.18 | [Shift Array Right](python/3.18-shift-array-right.md)                  | Rotation techniques with O(1) extra space.        |
| 3.19 | [Continuous Subarrays with Sum k](python/3.19-continuous-subarrays.md) | Prefix sum + hashmap counting approach.           |
| 3.20 | [Events](python/3.20-events.md)                                        | Interval scheduling and event-line strategies.    |
| 3.21 | [Merge Meetings](python/3.21-merge-meetings.md)                        | Interval merge logic after sorting by start.      |
| 3.22 | [Trie](python/3.22-trie.md)                                            | Prefix tree for fast string prefix queries.       |
| 3.23 | [Kadane's Algorithm](python/3.23-kadane.md)                            | Maximum subarray in linear time.                  |
| 3.24 | [Union Find / DSU](python/3.24-union-find.md)                          | Connectivity tracking with path compression.      |
| 3.25 | [Fast Power](python/3.25-fast-power.md)                                | Exponentiation by squaring in logarithmic time.   |
| 3.26 | [Fibonacci Golden](python/3.26-fibonacci-golden.md)                    | Closed-form Fibonacci intuition and caveats.      |
| 3.27 | [Basic Calculator](python/3.27-basic-calculator.md)                    | Expression parsing with stack/state handling.     |
| 3.28 | [Reverse Polish](python/3.28-reverse-polish.md)                        | Stack evaluation of postfix expressions.          |
| 3.29 | [Reservoir Sampling](python/3.29-reservoir-sampling.md)                | Uniform sampling from unknown-length streams.     |
| 3.30 | [String Subsequence](python/3.30-string-subsequence.md)                | Two-pointer checks and preprocessing methods.     |
| 3.31 | [Candy Crush](python/3.31-candy-crush.md)                              | Grid simulation with collapse/repeat mechanics.   |
| 3.32 | [Dutch Flag](python/3.32-dutch-flag.md)                                | Three-way partitioning in one pass.               |