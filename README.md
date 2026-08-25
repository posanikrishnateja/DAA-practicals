# DAA-practicals

## Practical 01 — DAA_Practical01.ipynb

### Bubble Sort

Bubble Sort is a simple comparison-based sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeated until the list is sorted. Bubble Sort is easy to implement but has a worst-case and average time complexity of O(n^2), so it is inefficient for large datasets.

### Insertion Sort

Insertion Sort builds the final sorted array one item at a time. It iterates through the array and, for each element, inserts it into the correct position relative to the already-sorted portion of the array. Insertion Sort performs well on small or nearly-sorted datasets and has a worst-case time complexity of O(n^2) and a best-case of O(n).

### Selection Sort

Selection Sort divides the array into a sorted and an unsorted portion. It repeatedly selects the minimum (or maximum) element from the unsorted portion and moves it to the end of the sorted portion. Selection Sort has a time complexity of O(n^2) for all cases and typically performs worse than more advanced algorithms on large inputs, but it does a minimal number of swaps.

### Quick Sort

Quick Sort is a highly efficient divide-and-conquer sorting algorithm. It selects a pivot element, partitions the array into elements less than and greater than the pivot, and then recursively sorts the partitions. Quick Sort has an average time complexity of O(n log n) but a worst-case of O(n^2) if poor pivots are chosen. With good pivot selection (randomized or median-of-three), it is usually very fast.

### Merge Sort

Merge Sort is a stable divide-and-conquer sorting algorithm that splits the array into smaller sub-arrays, sorts them, and then merges the sorted sub-arrays back together. Merge Sort guarantees O(n log n) time in all cases and is stable, but it requires additional O(n) space for merging.

## Practical 02 — DAA_Practical02.ipynb

Practical 02 explores core algorithm design techniques beyond simple sorting. This practical introduces and applies Greedy Algorithms, Dynamic Programming, and Divide-and-Conquer strategies to classical problems. Students implement, analyze, and compare solutions for each technique and learn when each approach is appropriate.

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

Feel free to tell me if you want different specific exercises added to Practical 02 (for example: more DP problems or graph-based greedy examples) or if you want the section placed elsewhere in the README.
