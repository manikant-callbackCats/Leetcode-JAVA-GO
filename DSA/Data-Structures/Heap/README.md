# Heap (Priority Queue)

## Overview

A **heap** is a complete binary tree that satisfies the heap property:
- **Min-Heap**: parent ≤ children (root is the minimum)
- **Max-Heap**: parent ≥ children (root is the maximum)

Heaps are typically implemented as arrays and are the underlying structure for **Priority Queues**.

## Complexity

| Operation      | Time Complexity |
|----------------|----------------|
| Insert         | O(log n)       |
| Delete (root)  | O(log n)       |
| Peek (root)    | O(1)           |
| Build Heap     | O(n)           |
| Heapify        | O(log n)       |
| Space          | O(n)           |

## Key Techniques

- **Top K Elements** – maintain a heap of size K
- **K-Way Merge** – merge K sorted lists using a min-heap
- **Median of Data Stream** – use a max-heap + min-heap
- **Dijkstra's Algorithm** – min-heap for shortest path

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 215 | [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium |
| 347 | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium |
| 295 | [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) | Hard |
| 23 | [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard |
| 1046 | [Last Stone Weight](https://leetcode.com/problems/last-stone-weight/) | Easy |
| 973 | [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) | Medium |
| 621 | [Task Scheduler](https://leetcode.com/problems/task-scheduler/) | Medium |
