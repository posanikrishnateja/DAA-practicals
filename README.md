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

Practical 03 focuses on foundational graph and tree algorithms, along with data-structure techniques that are widely used in real-world problem solving. The practical provides hands-on implementations and complexity analysis of core algorithms, and includes both basic and slightly more advanced topics to build intuition and algorithmic thinking.

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

If you'd like a different set of topics (for example: more on flow algorithms like Ford–Fulkerson, or graph algorithms for directed graphs), tell me and I can update this section or add extra exercises.
