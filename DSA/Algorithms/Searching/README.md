# Searching Algorithms

## Overview

Searching algorithms find an element or a set of elements within a data structure.

## Common Algorithms

| Algorithm     | Time Complexity | Space | Requirement         |
|---------------|----------------|-------|---------------------|
| Linear Search | O(n)           | O(1)  | None                |
| Binary Search | O(log n)       | O(1)  | Sorted array        |
| Ternary Search| O(log₃ n)      | O(1)  | Unimodal function   |

## Binary Search Variants

- **Classic** – find exact target index
- **Left Bound** – find first occurrence
- **Right Bound** – find last occurrence
- **Rotated Array** – search in rotated sorted array
- **On Answer** – binary search on the answer space (e.g., minimum capacity)

## Key Template (Binary Search)

```
left = 0, right = n - 1
while left <= right:
    mid = left + (right - left) / 2
    if arr[mid] == target: return mid
    elif arr[mid] < target: left = mid + 1
    else: right = mid - 1
return -1
```

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 704 | [Binary Search](https://leetcode.com/problems/binary-search/) | Easy |
| 33 | [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium |
| 34 | [Find First and Last Position of Element](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | Medium |
| 153 | [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium |
| 162 | [Find Peak Element](https://leetcode.com/problems/find-peak-element/) | Medium |
| 410 | [Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/) | Hard |
| 4 | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
