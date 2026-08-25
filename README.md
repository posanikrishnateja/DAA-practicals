# DAA-practicals

## Practical 01 — DAA_Practical01.ipynb

### Bubble Sort

Bubble Sort is a simple comparison-based sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeate[...]

### Insertion Sort

Insertion Sort builds the final sorted array one item at a time. It iterates through the array and, for each element, inserts it into the correct position relative to the already-sorted portion of[...]

### Selection Sort

Selection Sort divides the array into a sorted and an unsorted portion. It repeatedly selects the minimum (or maximum) element from the unsorted portion and moves it to the end of the sorted porti[...]

### Quick Sort

Quick Sort is a highly efficient divide-and-conquer sorting algorithm. It selects a pivot element, partitions the array into elements less than and greater than the pivot, and then recursively sor[...]

### Merge Sort

Merge Sort is a stable divide-and-conquer sorting algorithm that splits the array into smaller sub-arrays, sorts them, and then merges the sorted sub-arrays back together. Merge Sort guarantees O([...]

## Practical 02 — DAA_Practical02.ipynb

Practical 02 explores core algorithm design techniques beyond simple sorting. This practical introduces and applies Greedy Algorithms, Dynamic Programming, and Divide-and-Conquer strategies to cla[...]

Topics covered (examples):

- Greedy Algorithms
  - Activity Selection: choosing the maximum number of non-overlapping intervals using a greedy choice by finish time.
  - Fractional Knapsack: selecting items to maximize value when fractions are allowed, using value/weight ratio.
  - Huffman Coding (overview): building an optimal prefix code for lossless data compression using a greedy priority-queue approach.

- Dynamic Programming
  - 0/1 Knapsack: optimal selection of items without splitting, using DP to trade time for correctness.
  - Longest Common Subsequence (LCS): finding the longest subsequence common to two sequences using DP table construction.
  - Matrix Chain Multiplication (overview): parenthesization problem to minimize scalar multiplications through DP.

- Divide and Conquer (additional practice)
  - Binary Search: efficient searching in sorted arrays (O(log n)).
  - Fast Exponentiation (binary exponentiation): computing powers in O(log n) time.

Learning outcomes:

- Implement and test representative algorithms for each technique.
- Analyze time and space complexity; compare greedy vs dynamic programming trade-offs.
- Recognize problem characteristics that make greedy approaches correct, versus those requiring dynamic programming.

Feel free to tell me if you want different specific exercises added to Practical 02 (for example: more DP problems or graph-based greedy examples) or if you want the section placed elsewhere in th[...]

## Practical 03 — DAA_Practical03.ipynb

Practical 03 focuses on foundational graph and tree algorithms, along with data-structure techniques that are widely used in real-world problem solving. The practical provides hands-on implementat[...]

Topics covered (examples):

- Graph Algorithms
  - Breadth-First Search (BFS): level-order traversal for shortest paths in unweighted graphs.
  - Depth-First Search (DFS): traversal, connectivity, and use in topological sorting and cycle detection.
  - Dijkstra's Algorithm: single-source shortest paths for weighted graphs with non-negative weights.
  - Minimum Spanning Trees (Prim's and Kruskal's): building MSTs using greedy approaches and union-find.
  - Topological Sort: ordering of DAGs and its applications.

- Tree and Heap Structures
  - Binary Search Trees (BST): insertion, deletion, search, and in-order traversal.
  - Balanced trees (overview): motivation and basics of AVL/Red-Black trees.
  - Heaps and Priority Queues: heap operations and applications in scheduling and graph algorithms.

- Disjoint Set (Union-Find)
  - Union by rank and path compression: efficient set union and find operations, and use in Kruskal's algorithm.

- Hashing and Maps
  - Hash tables basics: collision resolution strategies and complexity trade-offs.

Learning outcomes:

- Implement and debug BFS, DFS, Dijkstra, Prim, and Kruskal with example inputs.
- Use and reason about trees, heaps, and disjoint-set data structures in algorithm design.
- Analyze time and space complexity of graph algorithms; understand when each algorithm is appropriate.
- Apply MST and shortest-path algorithms to model and solve practical problems (network design, routing).

Suggested exercises:

- Compute shortest paths on sample weighted graphs using Dijkstra and compare with BFS on unweighted graphs.
- Build MST using Kruskal and Prim on the same graph and compare results and performance.
- Implement union-find with path compression and use it to detect cycles in undirected graphs.
- Practice topological sorting on task-scheduling examples.

If you'd like a different set of topics (for example: more on flow algorithms like Ford–Fulkerson, or graph algorithms for directed graphs), tell me and I can update this section or add extra ex[...]

## Practical 04 — DAA_Practical04.ipynb

Practical 04 covers advanced algorithmic techniques and important data structures that extend the foundations from the earlier practicals. The goal is to expose students to string algorithms, rang[...]

Topics covered (examples):

- String and Pattern Matching
  - Knuth–Morris–Pratt (KMP): efficient linear-time pattern search using prefix-function (failure function).
  - Rabin–Karp (overview): rolling-hash based string matching useful for multiple-pattern search and plagiarism detection.
  - Trie and Suffix Array basics: prefix trees for fast prefix queries and suffix arrays for substring problems (overview).

- Range Queries and Trees
  - Segment Trees: range-sum, range-min, and range-update variants; building and querying in O(log n).
  - Fenwick Tree (Binary Indexed Tree): efficient prefix-sum queries and point updates with O(log n) complexity.

- Randomized and Approximation Algorithms
  - Randomized Quickselect and randomized hashing techniques.
  - Approximation algorithms overview (e.g., greedy approximation for set cover) and performance guarantees.

- Network Flow and Matching (introductory)
  - Max Flow (Ford–Fulkerson / Edmonds–Karp overview): modeling and solving flow problems; applications to bipartite matching.
  - Bipartite Matching basics: greedy matching and augmenting paths.

- Complexity and NP-Completeness (overview)
  - P vs NP intuition, reductions, and common NP-complete problems (SAT, Vertex Cover, Hamiltonian Path) with practical implications.

Learning outcomes:

- Implement and test core string algorithms (KMP, rolling hash) and understand use-cases for suffix arrays/tries.
- Build and use segment trees and Fenwick trees for efficient range queries and updates.
- Understand randomized algorithms' role and basic approximation guarantees for hard problems.
- Model simple flow problems and apply max-flow / matching techniques on small examples.
- Gain a practical intuition for computational complexity and why some problems require approximation or heuristics.

Suggested exercises:

- Implement KMP and use it to find all occurrences of a pattern in a text.
- Build a segment tree supporting range-sum queries and point updates; compare performance with a naive approach.
- Solve a small maximum bipartite matching instance using Ford–Fulkerson or a simple augmenting-path method.
- Implement a Fenwick Tree and use it to answer prefix-sum queries on dynamic arrays.
- Try an approximation algorithm for a small set cover instance and compare with the optimal solution for tiny inputs.

If you want additional topics in Practical 04 (for example: deeper coverage of suffix trees, streaming algorithms, or more on approximation schemes), tell me and I will extend this section.

## Practical 07 — DAA_Practical07.ipynb

Practical 07 builds on earlier practicals and covers advanced algorithmic topics and data structures that are critical for competitive programming and real-world systems. The practical emphasizes problem-solving patterns, performance engineering, and algorithms that scale to large inputs.

Topics covered (examples):

- Advanced Graph Algorithms
  - Maximum Flow and Minimum Cut (Dinic's algorithm, Push–Relabel overview): efficient algorithms for large flow networks and practical tips for implementation.
  - Minimum Cost Flow (overview): modeling costs with flows and brief examples.
  - Strongly Connected Components (Kosaraju / Tarjan) and bridges/articulation points.
  - Advanced shortest paths: Johnson's algorithm, usages of potentials, and handling negative edges.

- Advanced Data Structures
  - Heavy-Light Decomposition (HLD): path and subtree queries on trees.
  - Segment Trees with lazy propagation, persistent segment trees, and segment-tree-of-vectors techniques.
  - Binary Indexed Tree extensions, ordered statistic trees (policy-based data structures / order-stat tree), and treaps/splay trees.

- String & Number-Theory Algorithms
  - Suffix Automaton / Suffix Array (construction and applications) and suffix tree concepts overview.
  - Z-algorithm and KMP revisited for advanced pattern tasks.
  - Fast Fourier Transform (FFT) / Number Theoretic Transform (NTT) for polynomial multiplication and convolution problems.

- Advanced Dynamic Programming
  - Bitmask DP (TSP-style problems), DP on trees, and divide-and-conquer DP optimization.
  - Knuth optimization, convex-hull trick, and other speedups for specific DP recurrences.

- Offline Algorithms and Query Techniques
  - Mo's algorithm for offline range queries and variants for trees.
  - Sweep-line algorithms and event-based processing for geometry and interval problems.

- Computational Geometry (introductory to intermediate)
  - Convex hull (Graham scan / Andrew's monotone chain), line intersection, and rotating calipers applications.

- Algorithm Engineering & Complexity
  - Practical performance considerations: cache friendliness, constant-factor optimizations, and input/output techniques.
  - Approximation algorithms and heuristics for NP-hard problems; randomized algorithms and probabilistic analysis.

Learning outcomes:

- Implement and apply advanced graph algorithms (Dinic, SCCs, min-cost flow) to model real problems.
- Use heavy-light decomposition and persistent segment trees to answer complex tree and range queries efficiently.
- Apply FFT/NTT to solve convolution and polynomial problems and use advanced DP optimizations to speed up solutions.
- Understand offline query strategies (Mo's, sweep-line) and basic computational geometry tools for contest tasks.
- Make pragmatic performance trade-offs and reason about algorithmic constants and memory usage for large inputs.

Suggested exercises:

- Implement Dinic's algorithm and solve a max-flow example; compare with Edmonds–Karp on dense vs sparse graphs.
- Build a heavy-light decomposition on a tree and support path-sum and subtree-update queries.
- Use FFT/NTT to multiply large polynomials (or multiply big integers) and compare with naive convolution.
- Solve a TSP-like DP with bitmasking on small n, and implement divide-and-conquer DP optimization on a sample recurrence.
- Apply Mo's algorithm to answer offline range query problems and extend it to tree queries.
- Implement a persistent segment tree to answer historical range queries.

If you want different topics in Practical 07 (for example: deeper coverage of parallel/distributed algorithms, advanced flow algorithms, or more geometry), tell me and I can adjust the section or add specific exercises.
