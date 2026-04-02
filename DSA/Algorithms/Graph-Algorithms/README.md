# Graph Algorithms

## Overview

Graph algorithms solve problems related to traversal, shortest paths, connectivity, and topological ordering of graphs.

## Core Algorithms

### Traversal
| Algorithm | Time     | Space | Use Case |
|-----------|----------|-------|----------|
| BFS       | O(V + E) | O(V)  | Shortest path (unweighted), level-order |
| DFS       | O(V + E) | O(V)  | Cycle detection, connectivity, topological sort |

### Shortest Path
| Algorithm      | Time             | Handles Negative Weights |
|----------------|------------------|--------------------------|
| BFS            | O(V + E)         | No (unweighted only)     |
| Dijkstra       | O((V+E) log V)   | No                       |
| Bellman-Ford   | O(V · E)         | Yes                      |
| Floyd-Warshall | O(V³)            | Yes (all pairs)          |

### Minimum Spanning Tree
| Algorithm | Time           | Approach |
|-----------|----------------|----------|
| Kruskal   | O(E log E)     | Sort edges, Union-Find |
| Prim      | O((V+E) log V) | Greedy with min-heap |

### Other
- **Topological Sort** – Kahn's algorithm (BFS) or DFS post-order
- **Union-Find (DSU)** – cycle detection, connected components
- **Tarjan's / Kosaraju's** – Strongly Connected Components (SCC)

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 200 | [Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium |
| 207 | [Course Schedule (Topological Sort)](https://leetcode.com/problems/course-schedule/) | Medium |
| 743 | [Network Delay Time (Dijkstra)](https://leetcode.com/problems/network-delay-time/) | Medium |
| 787 | [Cheapest Flights Within K Stops (Bellman-Ford)](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | Medium |
| 684 | [Redundant Connection (Union-Find)](https://leetcode.com/problems/redundant-connection/) | Medium |
| 1584 | [Min Cost to Connect All Points (Prim/Kruskal)](https://leetcode.com/problems/min-cost-to-connect-all-points/) | Medium |
| 127 | [Word Ladder (BFS)](https://leetcode.com/problems/word-ladder/) | Hard |
| 332 | [Reconstruct Itinerary (Eulerian Path)](https://leetcode.com/problems/reconstruct-itinerary/) | Hard |
