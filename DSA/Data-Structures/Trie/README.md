# Trie (Prefix Tree)

## Overview

A **Trie** (pronounced "try") is a tree-like data structure used to store strings where each node represents a character. It is efficient for **prefix-based search**, **autocomplete**, and **spell checking**.

## Structure

- Each node stores a character and a map/array of children
- A boolean flag (`isEnd`) marks the end of a valid word

## Complexity

| Operation | Time Complexity |
|-----------|----------------|
| Insert    | O(m) where m = word length |
| Search    | O(m)           |
| StartsWith| O(m)           |
| Delete    | O(m)           |
| Space     | O(n × m) total for n words |

## Key Techniques

- **Word Search / Dictionary** – fast prefix and exact match
- **Autocomplete** – return all words with a given prefix
- **XOR Maximum** – store binary representation to find max XOR pair

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 208 | [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) | Medium |
| 212 | [Word Search II](https://leetcode.com/problems/word-search-ii/) | Hard |
| 211 | [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/) | Medium |
| 421 | [Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | Medium |
| 720 | [Longest Word in Dictionary](https://leetcode.com/problems/longest-word-in-dictionary/) | Medium |
