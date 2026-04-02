# Two Pointers

## Overview

The **Two Pointers** technique uses two indices to traverse a data structure (usually an array or string) simultaneously, reducing time complexity from O(n²) to O(n).

## Patterns

| Pattern | Description | Example |
|---------|-------------|---------|
| Opposite ends | Left and right move toward center | Two Sum (sorted), Container With Most Water |
| Same direction | Both pointers move forward, different speeds | Fast & Slow (Floyd's Cycle) |
| Sliding window | Expand/shrink a window | Longest substring without repeats |
| Merge-style | Pointers over two separate arrays | Merge two sorted arrays |

## When to Use

- Array/string is **sorted** (opposite direction pointers)
- Finding **pairs** or **triplets** summing to a target
- Detecting **cycles** in linked lists
- Comparing characters from both ends (palindrome check)

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 167 | [Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | Medium |
| 15 | [3Sum](https://leetcode.com/problems/3sum/) | Medium |
| 11 | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium |
| 125 | [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) | Easy |
| 42 | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard |
| 26 | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy |
| 88 | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy |
| 18 | [4Sum](https://leetcode.com/problems/4sum/) | Medium |
