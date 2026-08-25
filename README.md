# DAA-practicals

## Practical 01 — DAA_Practical01.ipynb
## Bubble Sort

**Bubble Sort** is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process continues until the list is sorted. It has a time complexity of O(n²) in the worst and average cases, making it inefficient for large datasets. However, it's easy to understand and implement, making it useful for educational purposes.

## Insertion Sort

**Insertion Sort** is a sorting algorithm that builds the final sorted array one item at a time. It iterates through an array, and for each element, it finds the correct position in the already-sorted portion of the array and inserts it there. The algorithm is efficient for small datasets and partially sorted arrays, with a time complexity of O(n²) in the worst case and O(n) in the best case. It's also stable and requires minimal extra space.

## Selection Sort

**Selection Sort** is an algorithm that divides the array into two portions: sorted and unsorted. It repeatedly finds the minimum element from the unsorted portion and moves it to the sorted portion. The process continues until the entire array is sorted. Selection Sort has a time complexity of O(n²) regardless of the input, making it less efficient than other sorting algorithms. However, it requires minimal memory and performs fewer swaps compared to bubble sort.

## Quick Sort

**Quick Sort** is a highly efficient sorting algorithm that uses the divide-and-conquer approach. It selects a pivot element and partitions the array around the pivot, then recursively sorts the sub-arrays. Quick Sort has an average time complexity of O(n log n), making it very efficient for large datasets. In the worst case, it can degrade to O(n²), but with good pivot selection strategies, this is rarely encountered. It's widely used in practice due to its speed and efficiency.

## Merge Sort

**Merge Sort** is a stable, divide-and-conquer sorting algorithm that divides the array into smaller sub-arrays, sorts them, and then merges them back together in sorted order. It guarantees O(n log n) time complexity in all cases (best, average, and worst), making it highly predictable and efficient for large datasets. Although it requires additional O(n) space for merging, its consistent performance and stability make it a preferred choice for many applications, especially when dealing with linked lists or external sorting.
