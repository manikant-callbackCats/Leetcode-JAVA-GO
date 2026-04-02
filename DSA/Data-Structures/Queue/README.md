# Queue

## Overview

A **queue** is a linear data structure that follows the **FIFO** (First In, First Out) principle. Elements are added at the rear and removed from the front.

## Types

- **Simple Queue** – standard FIFO
- **Circular Queue** – rear wraps around to the front
- **Deque (Double-Ended Queue)** – insert/delete from both ends
- **Priority Queue** – elements are dequeued by priority (implemented with a Heap)

## Complexity

| Operation   | Time Complexity |
|-------------|----------------|
| Enqueue     | O(1)           |
| Dequeue     | O(1)           |
| Peek/Front  | O(1)           |
| Search      | O(n)           |
| Space       | O(n)           |

## Key Techniques

- **BFS (Breadth-First Search)** – level-order traversal of trees and graphs
- **Sliding Window Maximum** – use a monotonic deque
- **Task Scheduling** – round-robin or priority-based

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 232 | [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/) | Easy |
| 102 | [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Medium |
| 239 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 622 | [Design Circular Queue](https://leetcode.com/problems/design-circular-queue/) | Medium |
| 346 | [Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/) | Easy |
