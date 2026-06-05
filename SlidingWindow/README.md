# LeetCode 3 - Longest Substring Without Repeating Characters

## Problem

Find the length of the longest substring without repeating characters.

### Example

Input:

```text
abcabcbb
```

Output:

```text
3
```

## Approach

- Use Sliding Window
- Use HashSet to store characters
- Expand window using right pointer
- Remove duplicates using left pointer

## Time Complexity

```text
O(n)
```

## Space Complexity

```text
O(n)
```