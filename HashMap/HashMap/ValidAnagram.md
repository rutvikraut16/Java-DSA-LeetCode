# Valid Anagram - LeetCode 242

## Problem

Check whether two strings are anagrams of each other.

Example:

Input:
s = "anagram"
t = "nagaram"

Output:
true

## Approach

1. Check lengths.
2. Store character frequencies using HashMap.
3. Decrease frequencies using second string.
4. If map becomes empty, strings are anagrams.

## Time Complexity

O(n)

## Space Complexity

O(n)

## Concepts

- HashMap
- Frequency Counting
- Strings