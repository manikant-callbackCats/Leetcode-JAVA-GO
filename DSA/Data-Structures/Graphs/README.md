# Graphs

## Overview

A **graph** is a collection of **vertices (nodes)** connected by **edges**. Graphs can be directed or undirected, weighted or unweighted.

## Representations

- **Adjacency List** – map of node → list of neighbors; space-efficient for sparse graphs
- **Adjacency Matrix** – 2D boolean/weight matrix; O(1) edge lookup
- **Edge List** – list of (u, v, weight) tuples

## Types

- **Directed / Undirected**
- **Weighted / Unweighted**
- **Cyclic / Acyclic (DAG)**
- **Connected / Disconnected**
- **Bipartite**

## Complexity

| Algorithm | Time       | Space  |
|-----------|------------|--------|
| BFS       | O(V + E)   | O(V)   |
| DFS       | O(V + E)   | O(V)   |
| Dijkstra  | O((V+E) log V) | O(V) |
| Bellman-Ford | O(V·E) | O(V)   |
| Floyd-Warshall | O(V³) | O(V²) |
| Topological Sort | O(V+E) | O(V) |
| Union-Find | O(α(n)) per op | O(V) |

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 200 | [Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium |
| 133 | [Clone Graph](https://leetcode.com/problems/clone-graph/) | Medium |
| 207 | [Course Schedule](https://leetcode.com/problems/course-schedule/) | Medium |
| 417 | [Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/) | Medium |
| 127 | [Word Ladder](https://leetcode.com/problems/word-ladder/) | Hard |
| 743 | [Network Delay Time](https://leetcode.com/problems/network-delay-time/) | Medium |
| 684 | [Redundant Connection](https://leetcode.com/problems/redundant-connection/) | Medium |
| 329 | [Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) | Hard |
