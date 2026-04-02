# Divide and Conquer

## Overview

**Divide and Conquer** is an algorithm design paradigm that:
1. **Divides** the problem into smaller subproblems
2. **Conquers** each subproblem recursively
3. **Combines** the results

## Characteristics

- Subproblems are **independent** (unlike DP where they overlap)
- Typically results in O(n log n) time complexity
- Naturally implemented with recursion

## Examples

| Algorithm        | Divide Strategy         | Time       |
|------------------|-------------------------|------------|
| Merge Sort       | Split in half           | O(n log n) |
| Quick Sort       | Partition around pivot  | O(n log n) avg |
| Binary Search    | Halve search space      | O(log n)   |
| Strassen's Matrix| Split matrix into 4     | O(n^2.81)  |
| Closest Pair     | Split points by x-coord | O(n log n) |

## Master Theorem (Recurrence)

For T(n) = aT(n/b) + f(n):
- If f(n) = O(n^(log_b a - ε)): T(n) = Θ(n^(log_b a))
- If f(n) = Θ(n^(log_b a)): T(n) = Θ(n^(log_b a) · log n)
- If f(n) = Ω(n^(log_b a + ε)): T(n) = Θ(f(n))

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 912 | [Sort an Array (Merge Sort)](https://leetcode.com/problems/sort-an-array/) | Medium |
| 4 | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard |
| 215 | [Kth Largest Element (Quick Select)](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 241 | [Different Ways to Add Parentheses](https://leetcode.com/problems/different-ways-to-add-parentheses/) | Medium |
| 395 | [Longest Substring with At Least K Repeating Characters](https://leetcode.com/problems/longest-substring-with-at-least-k-repeating-characters/) | Medium |
| 53 | [Maximum Subarray (D&C approach)](https://leetcode.com/problems/maximum-subarray/) | Medium |
