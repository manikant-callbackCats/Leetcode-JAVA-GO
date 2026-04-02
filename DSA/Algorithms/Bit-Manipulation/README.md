# Bit Manipulation

## Overview

**Bit manipulation** solves problems using bitwise operators directly on binary representations of integers. It is often used to achieve O(1) or O(log n) solutions that would otherwise require more complex logic.

## Bitwise Operators

| Operator | Symbol | Example (5 = 101, 3 = 011) |
|----------|--------|---------------------------|
| AND      | `&`    | 5 & 3 = 001 = 1           |
| OR       | `\|`   | 5 \| 3 = 111 = 7          |
| XOR      | `^`    | 5 ^ 3 = 110 = 6           |
| NOT      | `~`    | ~5 = -6 (two's complement)|
| Left Shift | `<<` | 5 << 1 = 1010 = 10        |
| Right Shift | `>>` | 5 >> 1 = 010 = 2         |

## Common Tricks

| Trick | Expression | Description |
|-------|------------|-------------|
| Check if even | `n & 1 == 0` | Last bit is 0 for even |
| Check if power of 2 | `n & (n-1) == 0` | Only one bit set |
| Clear lowest set bit | `n & (n-1)` | Removes the lowest 1 bit |
| Get lowest set bit | `n & (-n)` | Isolates the lowest 1 bit |
| XOR same values | `a ^ a == 0` | Cancels duplicates |
| XOR with 0 | `a ^ 0 == a` | Identity element |
| Count set bits | Brian Kernighan's algorithm | Loop: `n &= (n-1)` |

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 191 | [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy |
| 338 | [Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy |
| 136 | [Single Number](https://leetcode.com/problems/single-number/) | Easy |
| 190 | [Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy |
| 268 | [Missing Number](https://leetcode.com/problems/missing-number/) | Easy |
| 371 | [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/) | Medium |
| 137 | [Single Number II](https://leetcode.com/problems/single-number-ii/) | Medium |
| 260 | [Single Number III](https://leetcode.com/problems/single-number-iii/) | Medium |
| 421 | [Maximum XOR of Two Numbers in an Array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/) | Medium |
