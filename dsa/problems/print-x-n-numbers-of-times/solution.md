# Print X N numbers of times

## Problem Description
Given two integers X and N, print the value X on the screen N times. Separate each number by a single space.Do not add a space after the last number.After printing all N numbers, move to the next line.If N = 0, still move to the next line (print an empty line).

## Solution

```python
class Solution:
    # Function to print the value X on the screen N times
    def printX(self, X, N):
        # Loop to print the value X, N times
        for i in range(N):
            # Print the value X
            print(X, end='')
            
            # Print a space between numbers,
            # but not after the last one
            if i < N - 1:
                print(" ", end='')
        
        # Move to the next line after printing
        print()

# Creating an instance of Solution class 
sol = Solution()
X = 7
N = 5

# Function call to print the value X, N times
sol.printX(X, N)
```

## Problem Link
https://takeuforward.org/plus/dsa/problems/print-x-n-numbers-of-times?subject=dsa&category=beginner-problem&subcategory=language-basics&source=strivers-a2z-dsa-track&tab=submissions

## Stats
- Success: true
- Test Cases: 25
- Time: 0.017s
- Memory: 9.12 KiB
