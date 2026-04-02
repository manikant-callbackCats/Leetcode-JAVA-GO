# Greedy Algorithms

## Overview

A **greedy algorithm** makes the locally optimal choice at each step with the hope of finding a global optimum. Greedy works when the problem has the **greedy choice property** and **optimal substructure**.

## When to Use Greedy

- Interval scheduling / activity selection
- Minimum spanning tree (Kruskal, Prim)
- Shortest path (Dijkstra)
- Huffman encoding
- Job sequencing with deadlines

## Greedy vs DP

| Aspect | Greedy | Dynamic Programming |
|--------|--------|---------------------|
| Choice | Local optimum | Global optimum via subproblems |
| Revisit | No | Yes (memoization) |
| Efficiency | Usually faster | Can be slower |
| Correctness | Must prove greedy choice property | Always correct if states defined right |

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 455 | [Assign Cookies](https://leetcode.com/problems/assign-cookies/) | Easy |
| 121 | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy |
| 55 | [Jump Game](https://leetcode.com/problems/jump-game/) | Medium |
| 45 | [Jump Game II](https://leetcode.com/problems/jump-game-ii/) | Medium |
| 56 | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium |
| 435 | [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) | Medium |
| 134 | [Gas Station](https://leetcode.com/problems/gas-station/) | Medium |
| 135 | [Candy](https://leetcode.com/problems/candy/) | Hard |
| 406 | [Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/) | Medium |
