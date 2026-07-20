### Java cheatsheet for Interview Coding Problems / Competitive Programming

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
| 1.01 | [Literals](java/1.01-literals.md)                       | Number, string, boolean, and null literal forms.   |
| 1.02 | [Loops](java/1.02-loops.md)                             | `for`/`while` patterns and loop control usage.     |
| 1.03 | [Strings](java/1.03-strings.md)                         | Common string operations and interview tricks.     |
| 1.04 | [Slicing](java/1.04-slicing.md)                         | Substring and array range extraction.              |
| 1.05 | [Tuple](java/1.05-tuple.md)                             | Record-based pair/tuple patterns.                  |
| 1.06 | [Sort](java/1.06-sort.md)                               | Built-in sorting with comparators and custom order.|
| 1.07 | [Hash](java/1.07-hash.md)                               | HashMap-based lookup and counting.                 |
| 1.08 | [Set](java/1.08-set.md)                                 | Fast membership checks with HashSet.               |
| 1.09 | [List](java/1.09-list.md)                               | ArrayList operations and common methods.           |
| 1.10 | [Dict](java/1.10-dict.md)                               | Key-value operations and counting/grouping idioms. |
| 1.12 | [Binary Tree](java/1.12-binary-tree.md)                 | Binary tree traversal and recursion templates.     |
| 1.13 | [Graph](java/1.13-graph.md)                             | Graph modeling with BFS/DFS foundations.            |
| 1.14 | [PriorityQueue](java/1.14-heapq.md)                    | Priority queue operations with PriorityQueue.      |
| 1.15 | [Lambda](java/1.15-lambda.md)                           | Functional expressions for concise transformations.|
| 1.16 | [Zip](java/1.16-zip.md)                                 | Parallel iteration and matrix rotation.            |
| 1.17 | [Random](java/1.17-random.md)                           | Random generation and shuffle basics.              |
| 1.18 | [Constants](java/1.18-constants.md)                     | Common constants and practical conventions.         |
| 1.19 | [Ternary](java/1.19-ternary.md)                         | Inline conditional expression patterns.            |
| 1.20 | [Bitwise Operators](java/1.20-bitwise-operators.md)     | Bit manipulation operators and common tricks.      |
| 1.21 | [For Else](java/1.21-for-else.md)                       | Simulating for-else control flow with flags.       |
| 1.22 | [Modulo](java/1.22-modulo.md)                           | Mod arithmetic behavior and negative handling.     |
| 1.23 | [Any](java/1.23-any.md)                                 | Stream-based truth-testing with `anyMatch`.        |
| 1.24 | [All](java/1.24-all.md)                                 | Stream-based validation with `allMatch`.           |
| 1.25 | [Bisect](java/1.25-bisect.md)                           | Binary search and lower/upper bound templates.     |
| 1.26 | [Math](java/1.26-math.md)                               | Useful `Math` utilities for coding problems.       |
| 1.28 | [Iter](java/1.28-iter.md)                               | Iterator protocol and traversal patterns.          |
| 1.29 | [Map](java/1.29-map.md)                                 | Functional mapping with streams.                   |
| 1.30 | [Filter](java/1.30-filter.md)                           | Predicate-based filtering with streams.            |
| 1.31 | [Reduce](java/1.31-reduce.md)                           | Folding sequences into single accumulated results. |
| 1.33 | [Regular Expression](java/1.33-regular-expression.md)   | Pattern matching and replacement workflows.        |
| 1.34 | [Types](java/1.34-types.md)                             | Generic type declarations and common patterns.     |
| 1.35 | [Grids](java/1.35-grids.md)                             | Matrix navigation and 2D indexing patterns.        |

---

## 2. Collections

| No. | Topic                                      | What                                               |
|----:|--------------------------------------------|----------------------------------------------------|
| 2.1 | [Deque](java/2.1-deque.md)                 | O(1) operations from both ends with ArrayDeque.    |
| 2.2 | [Counter](java/2.2-counter.md)             | Frequency counting and top-k element patterns.     |
| 2.3 | [Default Dict](java/2.3-default-dict.md)   | Auto-initialized map with `computeIfAbsent`.       |

---

## 3. Algorithms

|  No. | Topic                                                                  | What                                              |
|-----:|------------------------------------------------------------------------|---------------------------------------------------|
| 3.01 | [General Tips](java/3.01-general-tips.md)                              | Practical interview heuristics and coding habits. |
| 3.02 | [Binary Search](java/3.02-binary-search.md)                           | Search on sorted/answer space with boundaries.    |
| 3.03 | [Binary Search Tree](java/3.03-binary-search-tree.md)                 | BST properties, traversal, and operations.        |
| 3.04 | [Topological Sort](java/3.04-topological-sort.md)                     | DAG ordering via indegree or DFS approach.        |
| 3.05 | [Sliding Window](java/3.05-sliding-window.md)                         | Subarray/substring optimization with windows.     |
| 3.06 | [Greedy](java/3.06-greedy.md)                                         | Local-optimal strategies and proof intuition.     |
| 3.07 | [Tree Tricks](java/3.07-tree-tricks.md)                               | Common tree shortcuts and recursion templates.    |
| 3.08 | [Anagrams](java/3.08-anagrams.md)                                     | Character-count/hash approaches for anagrams.     |
| 3.09 | [Dynamic Programming](java/3.09-dynamic-programming.md)               | State transitions, memoization, and tabulation.   |
| 3.10 | [Cyclic Sort](java/3.10-cyclic-sort.md)                               | In-place index placement for constrained arrays.  |
| 3.11 | [Quick Sort](java/3.11-quick-sort.md)                                  | Partition-based divide-and-conquer sorting.       |
| 3.12 | [Merge Sort](java/3.12-merge-sort.md)                                 | Stable divide-and-conquer sorting framework.      |
| 3.13 | [Merge K Sorted Arrays](java/3.13-merge-arrays.md)                    | Heap-based merging across multiple sorted lists.  |
| 3.14 | [Linked List](java/3.14-linked-list.md)                               | Pointer techniques for traversal and mutation.    |
| 3.15 | [Convert Base](java/3.15-convert-base.md)                             | Base conversion logic and number representation.  |
| 3.16 | [Parenthesis](java/3.16-parenthesis.md)                               | Stack-based validation and generation patterns.   |
| 3.17 | [Max Profit Stock](java/3.17-max-profit-stock.md)                     | Profit optimization across stock constraints.     |
| 3.18 | [Shift Array Right](java/3.18-shift-array-right.md)                   | Rotation techniques with O(1) extra space.        |
| 3.19 | [Continuous Subarrays with Sum k](java/3.19-continuous-subarrays.md)   | Prefix sum + hashmap counting approach.           |
| 3.20 | [Events](java/3.20-events.md)                                         | Interval scheduling and event-line strategies.    |
| 3.21 | [Merge Meetings](java/3.21-merge-meetings.md)                         | Interval merge logic after sorting by start.      |
| 3.22 | [Trie](java/3.22-trie.md)                                             | Prefix tree for fast string prefix queries.       |
| 3.23 | [Kadane's Algorithm](java/3.23-kadane.md)                             | Maximum subarray in linear time.                  |
| 3.24 | [Union Find / DSU](java/3.24-union-find.md)                           | Connectivity tracking with path compression.      |
| 3.25 | [Fast Power](java/3.25-fast-power.md)                                 | Exponentiation by squaring in logarithmic time.   |
| 3.26 | [Fibonacci Golden](java/3.26-fibonacci-golden.md)                     | Closed-form Fibonacci intuition and caveats.      |
| 3.27 | [Basic Calculator](java/3.27-basic-calculator.md)                     | Expression parsing with stack/state handling.     |
| 3.28 | [Reverse Polish](java/3.28-reverse-polish.md)                         | Stack evaluation of postfix expressions.          |
| 3.29 | [Reservoir Sampling](java/3.29-reservoir-sampling.md)                 | Uniform sampling from unknown-length streams.     |
| 3.30 | [String Subsequence](java/3.30-string-subsequence.md)                 | Two-pointer checks and preprocessing methods.     |
| 3.31 | [Candy Crush](java/3.31-candy-crush.md)                               | Stack-based consecutive duplicate removal.        |
| 3.32 | [Dutch Flag](java/3.32-dutch-flag.md)                                  | Three-way partitioning in one pass.               |
