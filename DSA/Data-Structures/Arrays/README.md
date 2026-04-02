# Arrays

## Overview

An **array** is a contiguous block of memory that stores elements of the same type. It provides O(1) access by index.

## Complexity

| Operation | Time Complexity |
|-----------|----------------|
| Access    | O(1)           |
| Search    | O(n)           |
| Insert (end) | O(1) amortized |
| Insert (middle) | O(n)     |
| Delete    | O(n)           |
| Space     | O(n)           |

## Key Techniques

- **Two Pointers** – left/right pointers moving toward each other
- **Sliding Window** – fixed or variable-size window over the array
- **Prefix Sum** – precompute cumulative sums for range queries
- **Kadane's Algorithm** – maximum subarray sum in O(n)

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 1 | [Two Sum](https://leetcode.com/problems/two-sum/) | Easy |
| 53 | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) | Medium |
| 121 | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy |
| 238 | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/) | Medium |
| 11 | [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) | Medium |
| 15 | [3Sum](https://leetcode.com/problems/3sum/) | Medium |
| 42 | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/) | Hard |
