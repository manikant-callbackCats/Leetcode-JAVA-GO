# Hash Table

## Overview

A **hash table** (hash map) stores key-value pairs and provides average O(1) time for insert, delete, and lookup using a hash function.

## Complexity

| Operation | Average | Worst Case |
|-----------|---------|------------|
| Insert    | O(1)    | O(n)       |
| Delete    | O(1)    | O(n)       |
| Search    | O(1)    | O(n)       |
| Space     | O(n)    | O(n)       |

> Worst case occurs due to hash collisions.

## Collision Resolution

- **Chaining** – each bucket stores a linked list of entries
- **Open Addressing** – probe for the next available slot (linear, quadratic, double hashing)

## Key Techniques

- **Frequency Count** – count occurrences of elements
- **Two Sum Pattern** – store complement in map for O(n) lookup
- **Grouping / Anagram Detection** – group by sorted key or character count
- **Sliding Window + HashMap** – track window state efficiently

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 1 | [Two Sum](https://leetcode.com/problems/two-sum/) | Easy |
| 49 | [Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Medium |
| 128 | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Medium |
| 347 | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Medium |
| 146 | [LRU Cache](https://leetcode.com/problems/lru-cache/) | Medium |
| 560 | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium |
| 76 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
