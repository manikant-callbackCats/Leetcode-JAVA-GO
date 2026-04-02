# Dynamic Programming (DP)

## Overview

**Dynamic Programming** is an optimization technique that solves complex problems by breaking them into overlapping subproblems and storing their results to avoid redundant computation.

## Approaches

- **Top-Down (Memoization)** – recursive + cache results in a memo table
- **Bottom-Up (Tabulation)** – build up results from base cases iteratively

## Identifying DP Problems

A problem is likely a DP problem if it asks for:
- Count of ways
- Minimum / Maximum value
- True/False feasibility
- ... and has **overlapping subproblems** and **optimal substructure**

## Common Patterns

| Pattern | Examples |
|---------|----------|
| 1D DP | Climbing Stairs, House Robber |
| 2D DP / Grid | Unique Paths, Edit Distance |
| Subsequence | LCS, LIS, Edit Distance |
| Knapsack (0/1) | Subset Sum, Partition Equal Subset |
| Unbounded Knapsack | Coin Change, Combination Sum IV |
| DP on Trees | Diameter, Max Path Sum |
| Interval DP | Burst Balloons, Matrix Chain Multiplication |
| Bitmask DP | Travelling Salesman, Assignment Problem |

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 70 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy |
| 198 | [House Robber](https://leetcode.com/problems/house-robber/) | Medium |
| 322 | [Coin Change](https://leetcode.com/problems/coin-change/) | Medium |
| 300 | [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium |
| 1143 | [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) | Medium |
| 416 | [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) | Medium |
| 72 | [Edit Distance](https://leetcode.com/problems/edit-distance/) | Medium |
| 312 | [Burst Balloons](https://leetcode.com/problems/burst-balloons/) | Hard |
| 10 | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | Hard |
