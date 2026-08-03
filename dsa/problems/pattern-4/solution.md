# Pattern 4

## Problem Description
Given an integer n. You need to recreate the pattern given below for any value of N. Let's say for N = 5, the pattern should look like as below:122333444455555Print the pattern in the function given to you.

## Solution

```python
class Solution:
    def pattern4(self, n):
        for i in range(1, n + 1):
            for j in range(1, i + 1):
                print(i, end="")
            print()

```

## Problem Link
https://takeuforward.org/plus/dsa/problems/pattern-4?subject=dsa&category=beginner-problem&subcategory=patterns&tab=submissions

## Stats
- Success: true
- Test Cases: 100
- Time: 0.071s
- Memory: 9.38 KiB
