# 1. Two Sum

Difficulty: Easy

## Pattern

Hash map.

## Approach

Store each number and its index in a dictionary.

For each number, calculate the value needed to reach the target.
If that value is already in the dictionary, return its index and the current index.

## Complexity

Time: O(n)

Space: O(n)