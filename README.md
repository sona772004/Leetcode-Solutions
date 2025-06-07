# Leetcode-Solutions
Collection of my solutions to LeetCode problems with explanations and categorized folders.
# LeetCode Solutions 🧠

This repository contains my personal solutions to problems on [LeetCode](https://leetcode.com). Solutions are written in Python and organized by difficulty.

## 📁 Structure

- `Easy/` – beginner-friendly problems
- `Medium/` – intermediate problems
- `Hard/` – advanced problems

## 📌 Progress Tracker

| Difficulty | Solved |
|------------|--------|
| Easy       | 15     |
| Medium     | 10     |
| Hard       | 3      |

## 🧩 Sample File Format

```python
"""
Problem: Two Sum
LeetCode: https://leetcode.com/problems/two-sum/
Difficulty: Easy
"""

def twoSum(nums, target):
    hashmap = {}
    for i, num in enumerate(nums):
        diff = target - num
        if diff in hashmap:
            return [hashmap[diff], i]
        hashmap[num] = i

