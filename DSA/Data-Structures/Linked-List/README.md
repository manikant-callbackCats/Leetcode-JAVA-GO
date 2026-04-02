# Linked List

## Overview

A **linked list** is a linear data structure where each element (node) contains a value and a pointer to the next node. Unlike arrays, nodes are not stored in contiguous memory.

## Types

- **Singly Linked List** – each node points to the next
- **Doubly Linked List** – each node points to both next and previous
- **Circular Linked List** – the last node points back to the head

## Complexity

| Operation       | Time Complexity |
|-----------------|----------------|
| Access          | O(n)           |
| Search          | O(n)           |
| Insert (head)   | O(1)           |
| Insert (tail)   | O(1) with tail pointer |
| Delete (head)   | O(1)           |
| Delete (middle) | O(n)           |
| Space           | O(n)           |

## Key Techniques

- **Fast & Slow Pointers (Floyd's Cycle)** – detect cycles, find middle
- **Reverse a Linked List** – iterative or recursive
- **Merge Two Sorted Lists**
- **Dummy Node** – simplify edge cases at the head

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 206 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy |
| 21 | [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy |
| 141 | [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) | Easy |
| 19 | [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium |
| 23 | [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard |
| 142 | [Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) | Medium |
| 25 | [Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) | Hard |
