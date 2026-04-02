# Backtracking

## Overview

**Backtracking** is an algorithmic technique that builds a solution incrementally and abandons a path ("backtracks") as soon as it determines the path cannot lead to a valid solution.

## Template

```
function backtrack(state, choices):
    if isGoal(state):
        addToResult(state)
        return
    for choice in choices:
        if isValid(state, choice):
            makeChoice(state, choice)
            backtrack(state, remainingChoices)
            undoChoice(state, choice)   // backtrack
```

## Common Patterns

- **Subsets** – generate all subsets of a set
- **Permutations** – generate all permutations
- **Combinations** – generate all combinations of size k
- **Constraint Satisfaction** – N-Queens, Sudoku, Word Search

## Time Complexity

- Subsets: O(2ⁿ)
- Permutations: O(n!)
- Combinations: O(C(n, k))

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 78 | [Subsets](https://leetcode.com/problems/subsets/) | Medium |
| 46 | [Permutations](https://leetcode.com/problems/permutations/) | Medium |
| 77 | [Combinations](https://leetcode.com/problems/combinations/) | Medium |
| 39 | [Combination Sum](https://leetcode.com/problems/combination-sum/) | Medium |
| 51 | [N-Queens](https://leetcode.com/problems/n-queens/) | Hard |
| 37 | [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/) | Hard |
| 79 | [Word Search](https://leetcode.com/problems/word-search/) | Medium |
| 131 | [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/) | Medium |
