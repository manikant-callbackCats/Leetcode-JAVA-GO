# Trees

## Overview

A **tree** is a hierarchical data structure with a root node and subtrees of children. It is a special case of a graph with no cycles.

## Types

- **Binary Tree** – each node has at most 2 children
- **Binary Search Tree (BST)** – left < root < right
- **AVL Tree** – self-balancing BST
- **Red-Black Tree** – self-balancing BST used in most language libraries
- **N-ary Tree** – each node can have up to N children
- **Segment Tree** – for range queries and updates
- **Fenwick Tree (BIT)** – efficient prefix sum queries

## Complexity (BST average case)

| Operation | Time Complexity |
|-----------|----------------|
| Access    | O(log n)       |
| Search    | O(log n)       |
| Insert    | O(log n)       |
| Delete    | O(log n)       |
| Space     | O(n)           |

## Traversals

| Traversal    | Order                   | Use Case                  |
|--------------|-------------------------|---------------------------|
| In-order     | Left → Root → Right     | Sorted output from BST    |
| Pre-order    | Root → Left → Right     | Copy/serialize a tree     |
| Post-order   | Left → Right → Root     | Delete a tree             |
| Level-order  | BFS level by level      | Shortest path in unweighted tree |

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 104 | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy |
| 226 | [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/) | Easy |
| 100 | [Same Tree](https://leetcode.com/problems/same-tree/) | Easy |
| 102 | [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Medium |
| 98 | [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) | Medium |
| 235 | [Lowest Common Ancestor of a BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | Medium |
| 124 | [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard |
| 297 | [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard |
