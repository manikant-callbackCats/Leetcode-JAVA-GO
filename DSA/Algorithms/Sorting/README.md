# Sorting Algorithms

## Overview

Sorting algorithms arrange elements in a defined order (ascending or descending).

## Comparison

| Algorithm      | Best      | Average   | Worst     | Space   | Stable |
|----------------|-----------|-----------|-----------|---------|--------|
| Bubble Sort    | O(n)      | O(n²)     | O(n²)     | O(1)    | Yes    |
| Selection Sort | O(n²)     | O(n²)     | O(n²)     | O(1)    | No     |
| Insertion Sort | O(n)      | O(n²)     | O(n²)     | O(1)    | Yes    |
| Merge Sort     | O(n log n)| O(n log n)| O(n log n)| O(n)    | Yes    |
| Quick Sort     | O(n log n)| O(n log n)| O(n²)     | O(log n)| No     |
| Heap Sort      | O(n log n)| O(n log n)| O(n log n)| O(1)    | No     |
| Counting Sort  | O(n+k)    | O(n+k)    | O(n+k)    | O(k)    | Yes    |
| Radix Sort     | O(nk)     | O(nk)     | O(nk)     | O(n+k)  | Yes    |

## Key Concepts

- **Stable Sort** – equal elements preserve their relative order
- **In-place Sort** – uses O(1) extra space
- **Divide and Conquer** – Merge Sort and Quick Sort use this approach

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 912 | [Sort an Array](https://leetcode.com/problems/sort-an-array/) | Medium |
| 75 | [Sort Colors](https://leetcode.com/problems/sort-colors/) | Medium |
| 56 | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |
| 147 | [Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/) | Medium |
| 315 | [Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) | Hard |
