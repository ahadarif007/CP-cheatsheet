# Competitive Programming Cheatsheet

Quick-reference snippets for coding interviews and competitive programming. Each language covers the same topics: language mechanics, collections, and common algorithms.

## How

This cheatsheet was built while solving LeetCode-style problems across multiple languages. It only contains syntax and patterns that came up while solving actual problems, keeping it a small, high-frequency subset rather than a comprehensive reference. Recording these snippets also helped commit them to memory.

## Why

Following the [rule of least power](https://en.wikipedia.org/wiki/Rule_of_least_power), Python is listed first as the primary language due to its concise syntax that resembles pseudocode and its rich standard library, making it the most expressive choice for interviews. Java, C#, and JavaScript are included as alternatives with their own strengths: Java and C# offer strong typing and predictable performance, while JavaScript provides fast iteration and expressive built-ins. When runtime performance matters, compiled languages like Java or C# can be significantly faster than Python on competitive programming judges.

## Languages

| Language | Cheatsheet |
|----------|------------|
| Python | [readme-python.md](readme-python.md) |
| Java | [readme-java.md](readme-java.md) |
| C# | [readme-csharp.md](readme-csharp.md) |
| JavaScript | [readme-javascript.md](readme-javascript.md) |

---

## Topics Covered

### Language Mechanics

| No. | Topic | Python | Java | C# | JS | What |
|----:|-------|:------:|:----:|:--:|:--:|------|
| 1.01 | Literals | [view](python/1.01-literals.md) | [view](java/1.01-literals.md) | [view](csharp/1.01-literals.md) | [view](java-script/1.01-literals.md) | Number, string, boolean, and null literal forms. |
| 1.02 | Loops | [view](python/1.02-loops.md) | [view](java/1.02-loops.md) | [view](csharp/1.02-loops.md) | [view](java-script/1.02-loops.md) | `for`/`while` patterns and loop control usage. |
| 1.03 | Strings | [view](python/1.03-strings.md) | [view](java/1.03-strings.md) | [view](csharp/1.03-strings.md) | [view](java-script/1.03-strings.md) | Common string operations and interview tricks. |
| 1.04 | Slicing | [view](python/1.04-slicing.md) | [view](java/1.04-slicing.md) | [view](csharp/1.04-slicing.md) | [view](java-script/1.04-slicing.md) | Slice syntax for arrays/strings and edge cases. |
| 1.05 | Tuple | [view](python/1.05-tuple.md) | [view](java/1.05-tuple.md) | [view](csharp/1.05-tuple.md) | [view](java-script/1.05-tuple.md) | Immutable sequences and unpacking patterns. |
| 1.06 | Sort | [view](python/1.06-sort.md) | [view](java/1.06-sort.md) | [view](csharp/1.06-sort.md) | [view](java-script/1.06-sort.md) | Built-in sorting with keys and custom order. |
| 1.07 | Hash | [view](python/1.07-hash.md) | [view](java/1.07-hash.md) | [view](csharp/1.07-hash.md) | [view](java-script/1.07-hash.md) | Hashing basics and hash-based lookup usage. |
| 1.08 | Set | [view](python/1.08-set.md) | [view](java/1.08-set.md) | [view](csharp/1.08-set.md) | [view](java-script/1.08-set.md) | Fast membership checks and set operations. |
| 1.09 | List | [view](python/1.09-list.md) | [view](java/1.09-list.md) | [view](csharp/1.09-list.md) | [view](java-script/1.09-list.md) | Dynamic array operations and common methods. |
| 1.10 | Dict | [view](python/1.10-dict.md) | [view](java/1.10-dict.md) | [view](csharp/1.10-dict.md) | [view](java-script/1.10-dict.md) | Key-value operations and counting/grouping idioms. |
| 1.11 | Tree | [view](python/1.11-tree.md) | — | — | — | General tree representation and traversals. |
| 1.12 | Binary Tree | [view](python/1.12-binary-tree.md) | [view](java/1.12-binary-tree.md) | [view](csharp/1.12-binary-tree.md) | [view](java-script/1.12-binary-tree.md) | Binary tree traversal and recursion templates. |
| 1.13 | Graph | [view](python/1.13-graph.md) | [view](java/1.13-graph.md) | [view](csharp/1.13-graph.md) | [view](java-script/1.13-graph.md) | Graph modeling with BFS/DFS foundations. |
| 1.14 | Heap / PriorityQueue | [view](python/1.14-heapq.md) | [view](java/1.14-heapq.md) | [view](csharp/1.14-heapq.md) | [view](java-script/1.14-heapq.md) | Priority queue operations for min/max extraction. |
| 1.15 | Lambda | [view](python/1.15-lambda.md) | [view](java/1.15-lambda.md) | [view](csharp/1.15-lambda.md) | [view](java-script/1.15-lambda.md) | Anonymous functions for concise transformations. |
| 1.16 | Zip | [view](python/1.16-zip.md) | [view](java/1.16-zip.md) | [view](csharp/1.16-zip.md) | [view](java-script/1.16-zip.md) | Parallel iteration and tuple packing/unpacking. |
| 1.17 | Random | [view](python/1.17-random.md) | [view](java/1.17-random.md) | [view](csharp/1.17-random.md) | [view](java-script/1.17-random.md) | Random generation and controlled sampling basics. |
| 1.18 | Constants | [view](python/1.18-constants.md) | [view](java/1.18-constants.md) | [view](csharp/1.18-constants.md) | [view](java-script/1.18-constants.md) | Common constants and practical conventions. |
| 1.19 | Ternary | [view](python/1.19-ternary.md) | [view](java/1.19-ternary.md) | [view](csharp/1.19-ternary.md) | [view](java-script/1.19-ternary.md) | Inline conditional expression patterns. |
| 1.20 | Bitwise Operators | [view](python/1.20-bitwise-operators.md) | [view](java/1.20-bitwise-operators.md) | [view](csharp/1.20-bitwise-operators.md) | [view](java-script/1.20-bitwise-operators.md) | Bit manipulation operators and common tricks. |
| 1.21 | For Else | [view](python/1.21-for-else.md) | [view](java/1.21-for-else.md) | [view](csharp/1.21-for-else.md) | [view](java-script/1.21-for-else.md) | `for-else` control flow for search-style loops. |
| 1.22 | Modulo | [view](python/1.22-modulo.md) | [view](java/1.22-modulo.md) | [view](csharp/1.22-modulo.md) | [view](java-script/1.22-modulo.md) | Mod arithmetic behavior and interview use cases. |
| 1.23 | Any | [view](python/1.23-any.md) | [view](java/1.23-any.md) | [view](csharp/1.23-any.md) | [view](java-script/1.23-any.md) | Truth-testing iterable items with any/some. |
| 1.24 | All | [view](python/1.24-all.md) | [view](java/1.24-all.md) | [view](csharp/1.24-all.md) | [view](java-script/1.24-all.md) | Validating iterable items with all/every. |
| 1.25 | Bisect | [view](python/1.25-bisect.md) | [view](java/1.25-bisect.md) | [view](csharp/1.25-bisect.md) | [view](java-script/1.25-bisect.md) | Binary insertion/search in sorted arrays. |
| 1.26 | Math | [view](python/1.26-math.md) | [view](java/1.26-math.md) | [view](csharp/1.26-math.md) | [view](java-script/1.26-math.md) | Useful math utilities for coding problems. |
| 1.27 | Eval | [view](python/1.27-eval.md) | — | — | — | Expression evaluation basics and caution points. |
| 1.28 | Iter | [view](python/1.28-iter.md) | [view](java/1.28-iter.md) | [view](csharp/1.28-iter.md) | [view](java-script/1.28-iter.md) | Iterator protocol and lazy traversal patterns. |
| 1.29 | Map | [view](python/1.29-map.md) | [view](java/1.29-map.md) | [view](csharp/1.29-map.md) | [view](java-script/1.29-map.md) | Functional mapping across iterables. |
| 1.30 | Filter | [view](python/1.30-filter.md) | [view](java/1.30-filter.md) | [view](csharp/1.30-filter.md) | [view](java-script/1.30-filter.md) | Predicate-based filtering of iterable values. |
| 1.31 | Reduce | [view](python/1.31-reduce.md) | [view](java/1.31-reduce.md) | [view](csharp/1.31-reduce.md) | [view](java-script/1.31-reduce.md) | Folding sequences into single accumulated results. |
| 1.32 | itertools | [view](python/1.32-itertools.md) | — | — | — | Efficient combinatoric and iterator utilities. |
| 1.33 | Regular Expression | [view](python/1.33-regular-expression.md) | [view](java/1.33-regular-expression.md) | [view](csharp/1.33-regular-expression.md) | [view](java-script/1.33-regular-expression.md) | Pattern matching and extraction workflows. |
| 1.34 | Types | [view](python/1.34-types.md) | [view](java/1.34-types.md) | [view](csharp/1.34-types.md) | [view](java-script/1.34-types.md) | Type checks, conversions, and annotations basics. |
| 1.35 | Grids | [view](python/1.35-grids.md) | [view](java/1.35-grids.md) | [view](csharp/1.35-grids.md) | [view](java-script/1.35-grids.md) | Matrix navigation and 2D indexing patterns. |

### Collections

| No. | Topic | Python | Java | C# | JS | What |
|----:|-------|:------:|:----:|:--:|:--:|------|
| 2.1 | Deque | [view](python/2.1-deque.md) | [view](java/2.1-deque.md) | [view](csharp/2.1-deque.md) | [view](java-script/2.1-deque.md) | O(1) pops/appends from both ends. |
| 2.2 | Counter | [view](python/2.2-counter.md) | [view](java/2.2-counter.md) | [view](csharp/2.2-counter.md) | [view](java-script/2.2-counter.md) | Frequency counting and top-k element patterns. |
| 2.3 | Default Dict | [view](python/2.3-default-dict.md) | [view](java/2.3-default-dict.md) | [view](csharp/2.3-default-dict.md) | [view](java-script/2.3-default-dict.md) | Auto-initialized dictionary for grouping/counting. |

### Algorithms

| No. | Topic | Python | Java | C# | JS | What |
|----:|-------|:------:|:----:|:--:|:--:|------|
| 3.01 | General Tips | [view](python/3.01-general-tips.md) | [view](java/3.01-general-tips.md) | [view](csharp/3.01-general-tips.md) | [view](java-script/3.01-general-tips.md) | Practical interview heuristics and coding habits. |
| 3.02 | Binary Search | [view](python/3.02-binary-search.md) | [view](java/3.02-binary-search.md) | [view](csharp/3.02-binary-search.md) | [view](java-script/3.02-binary-search.md) | Search on sorted/answer space with boundaries. |
| 3.03 | Binary Search Tree | [view](python/3.03-binary-search-tree.md) | [view](java/3.03-binary-search-tree.md) | [view](csharp/3.03-binary-search-tree.md) | [view](java-script/3.03-binary-search-tree.md) | BST properties, traversal, and operations. |
| 3.04 | Topological Sort | [view](python/3.04-topological-sort.md) | [view](java/3.04-topological-sort.md) | [view](csharp/3.04-topological-sort.md) | [view](java-script/3.04-topological-sort.md) | DAG ordering via indegree or DFS approach. |
| 3.05 | Sliding Window | [view](python/3.05-sliding-window.md) | [view](java/3.05-sliding-window.md) | [view](csharp/3.05-sliding-window.md) | [view](java-script/3.05-sliding-window.md) | Subarray/substring optimization with windows. |
| 3.06 | Greedy | [view](python/3.06-greedy.md) | [view](java/3.06-greedy.md) | [view](csharp/3.06-greedy.md) | [view](java-script/3.06-greedy.md) | Local-optimal strategies and proof intuition. |
| 3.07 | Tree Tricks | [view](python/3.07-tree-tricks.md) | [view](java/3.07-tree-tricks.md) | [view](csharp/3.07-tree-tricks.md) | [view](java-script/3.07-tree-tricks.md) | Common tree shortcuts and recursion templates. |
| 3.08 | Anagrams | [view](python/3.08-anagrams.md) | [view](java/3.08-anagrams.md) | [view](csharp/3.08-anagrams.md) | [view](java-script/3.08-anagrams.md) | Character-count/hash approaches for anagrams. |
| 3.09 | Dynamic Programming | [view](python/3.09-dynamic-programming.md) | [view](java/3.09-dynamic-programming.md) | [view](csharp/3.09-dynamic-programming.md) | [view](java-script/3.09-dynamic-programming.md) | State transitions, memoization, and tabulation. |
| 3.10 | Cyclic Sort | [view](python/3.10-cyclic-sort.md) | [view](java/3.10-cyclic-sort.md) | [view](csharp/3.10-cyclic-sort.md) | [view](java-script/3.10-cyclic-sort.md) | In-place index placement for constrained arrays. |
| 3.11 | Quick Sort | [view](python/3.11-quick-sort.md) | [view](java/3.11-quick-sort.md) | [view](csharp/3.11-quick-sort.md) | [view](java-script/3.11-quick-sort.md) | Partition-based divide-and-conquer sorting. |
| 3.12 | Merge Sort | [view](python/3.12-merge-sort.md) | [view](java/3.12-merge-sort.md) | [view](csharp/3.12-merge-sort.md) | [view](java-script/3.12-merge-sort.md) | Stable divide-and-conquer sorting framework. |
| 3.13 | Merge K Sorted Arrays | [view](python/3.13-merge-arrays.md) | [view](java/3.13-merge-arrays.md) | [view](csharp/3.13-merge-arrays.md) | [view](java-script/3.13-merge-arrays.md) | Heap-based merging across multiple sorted lists. |
| 3.14 | Linked List | [view](python/3.14-linked-list.md) | [view](java/3.14-linked-list.md) | [view](csharp/3.14-linked-list.md) | [view](java-script/3.14-linked-list.md) | Pointer techniques for traversal and mutation. |
| 3.15 | Convert Base | [view](python/3.15-convert-base.md) | [view](java/3.15-convert-base.md) | [view](csharp/3.15-convert-base.md) | [view](java-script/3.15-convert-base.md) | Base conversion logic and number representation. |
| 3.16 | Parenthesis | [view](python/3.16-parenthesis.md) | [view](java/3.16-parenthesis.md) | [view](csharp/3.16-parenthesis.md) | [view](java-script/3.16-parenthesis.md) | Stack-based validation and generation patterns. |
| 3.17 | Max Profit Stock | [view](python/3.17-max-profit-stock.md) | [view](java/3.17-max-profit-stock.md) | [view](csharp/3.17-max-profit-stock.md) | [view](java-script/3.17-max-profit-stock.md) | Profit optimization across stock constraints. |
| 3.18 | Shift Array Right | [view](python/3.18-shift-array-right.md) | [view](java/3.18-shift-array-right.md) | [view](csharp/3.18-shift-array-right.md) | [view](java-script/3.18-shift-array-right.md) | Rotation techniques with O(1) extra space. |
| 3.19 | Continuous Subarrays | [view](python/3.19-continuous-subarrays.md) | [view](java/3.19-continuous-subarrays.md) | [view](csharp/3.19-continuous-subarrays.md) | [view](java-script/3.19-continuous-subarrays.md) | Prefix sum + hashmap counting approach. |
| 3.20 | Events | [view](python/3.20-events.md) | [view](java/3.20-events.md) | [view](csharp/3.20-events.md) | [view](java-script/3.20-events.md) | Interval scheduling and event-line strategies. |
| 3.21 | Merge Meetings | [view](python/3.21-merge-meetings.md) | [view](java/3.21-merge-meetings.md) | [view](csharp/3.21-merge-meetings.md) | [view](java-script/3.21-merge-meetings.md) | Interval merge logic after sorting by start. |
| 3.22 | Trie | [view](python/3.22-trie.md) | [view](java/3.22-trie.md) | [view](csharp/3.22-trie.md) | [view](java-script/3.22-trie.md) | Prefix tree for fast string prefix queries. |
| 3.23 | Kadane's Algorithm | [view](python/3.23-kadane.md) | [view](java/3.23-kadane.md) | [view](csharp/3.23-kadane.md) | [view](java-script/3.23-kadane.md) | Maximum subarray in linear time. |
| 3.24 | Union Find / DSU | [view](python/3.24-union-find.md) | [view](java/3.24-union-find.md) | [view](csharp/3.24-union-find.md) | [view](java-script/3.24-union-find.md) | Connectivity tracking with path compression. |
| 3.25 | Fast Power | [view](python/3.25-fast-power.md) | [view](java/3.25-fast-power.md) | [view](csharp/3.25-fast-power.md) | [view](java-script/3.25-fast-power.md) | Exponentiation by squaring in logarithmic time. |
| 3.26 | Fibonacci Golden | [view](python/3.26-fibonacci-golden.md) | [view](java/3.26-fibonacci-golden.md) | [view](csharp/3.26-fibonacci-golden.md) | [view](java-script/3.26-fibonacci-golden.md) | Closed-form Fibonacci intuition and caveats. |
| 3.27 | Basic Calculator | [view](python/3.27-basic-calculator.md) | [view](java/3.27-basic-calculator.md) | [view](csharp/3.27-basic-calculator.md) | [view](java-script/3.27-basic-calculator.md) | Expression parsing with stack/state handling. |
| 3.28 | Reverse Polish | [view](python/3.28-reverse-polish.md) | [view](java/3.28-reverse-polish.md) | [view](csharp/3.28-reverse-polish.md) | [view](java-script/3.28-reverse-polish.md) | Stack evaluation of postfix expressions. |
| 3.29 | Reservoir Sampling | [view](python/3.29-reservoir-sampling.md) | [view](java/3.29-reservoir-sampling.md) | [view](csharp/3.29-reservoir-sampling.md) | [view](java-script/3.29-reservoir-sampling.md) | Uniform sampling from unknown-length streams. |
| 3.30 | String Subsequence | [view](python/3.30-string-subsequence.md) | [view](java/3.30-string-subsequence.md) | [view](csharp/3.30-string-subsequence.md) | [view](java-script/3.30-string-subsequence.md) | Two-pointer checks and preprocessing methods. |
| 3.31 | Candy Crush | [view](python/3.31-candy-crush.md) | [view](java/3.31-candy-crush.md) | [view](csharp/3.31-candy-crush.md) | [view](java-script/3.31-candy-crush.md) | Stack-based consecutive duplicate removal. |
| 3.32 | Dutch Flag | [view](python/3.32-dutch-flag.md) | [view](java/3.32-dutch-flag.md) | [view](csharp/3.32-dutch-flag.md) | [view](java-script/3.32-dutch-flag.md) | Three-way partitioning in one pass. |
