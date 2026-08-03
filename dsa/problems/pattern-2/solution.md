# Pattern 2

## Problem Description
Given an integer n. You need to recreate the pattern given below for any value of N. Let's say for N = 5, the pattern should look like as below:***************Print the pattern in the function given to you.

## Solution

```python
class Solution:
    def pattern2(self, n):
        for i in range(n):
            for j in range(i+1):
                print("*" , end="")
            print()    
```

## Problem Link
https://takeuforward.org/plus/dsa/problems/pattern-2?subject=dsa&category=beginner-problem&subcategory=patterns&tab=submissions

## Stats
- Success: true
- Test Cases: 100
- Time: 0.070s
- Memory: 9.62 KiB
