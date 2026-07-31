# If ElseIf

## Problem Description
Given marks of a student, print on the screen:Grade A if marks >= 90Grade B if marks >= 70Grade C if marks >= 50Grade D if marks >= 35Fail, otherwise.For printing use:-for C++ : cout << variable_name;for Java : System.out.print();for Python : print()for Javascript : console.log()for C# : Console.WriteLine();for Go : fmt.Println()

## Solution

```python
class Solution:
    def studentGrade(self, marks):
        if marks >= 90:
            print('Grade A')
        elif marks >= 70:
            print('Grade B')
        elif marks >= 50:
            print('Grade C')
        elif marks >= 35:
            print('Grade D')
        else:
            print('Fail')

```

## Problem Link
https://takeuforward.org/plus/dsa/problems/if-elseif?subject=dsa&category=beginner-problem&subcategory=language-basics&source=strivers-a2z-dsa-track&tab=submissions

## Stats
- Success: true
- Test Cases: 22
- Time: 0.023s
- Memory: 9.62 KiB
