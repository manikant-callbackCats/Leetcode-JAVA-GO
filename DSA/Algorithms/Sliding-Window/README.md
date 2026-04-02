# Sliding Window

## Overview

The **Sliding Window** technique maintains a contiguous subarray (or substring) of variable or fixed size and slides it across the data to find an optimal result in O(n) time.

## Types

| Type | Description | Example |
|------|-------------|---------|
| Fixed Size | Window size k is constant | Max sum subarray of size k |
| Variable Size | Expand/shrink window based on condition | Longest substring without repeating chars |

## Template (Variable Window)

```
left = 0
for right in range(n):
    # expand: add arr[right] to window
    window.add(arr[right])

    while windowIsInvalid():
        # shrink: remove arr[left] from window
        window.remove(arr[left])
        left++

    updateResult(right - left + 1)
```

## When to Use

- Finding **longest/shortest subarray/substring** satisfying a condition
- **Maximum/minimum** sum of a subarray of size k
- **Distinct characters** count in a window

## Common LeetCode Problems

| # | Problem | Difficulty |
|---|---------|------------|
| 643 | [Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i/) | Easy |
| 3 | [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium |
| 424 | [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/) | Medium |
| 567 | [Permutation in String](https://leetcode.com/problems/permutation-in-string/) | Medium |
| 76 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard |
| 239 | [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/) | Hard |
| 438 | [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Medium |
