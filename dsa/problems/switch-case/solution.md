# Switch Case

## Problem Description
Given the integer day denoting the day number, print on the screen which day of the week it is. Week starts from Monday and for values greater than 7 or less than 1, print Invalid.Ensure only the 1st letter of the answer is capitalised.For printing use:-for C++ : cout << variable_name;for Java : System.out.print();for Python : print()for Javascript : console.log()

## Solution

```python
class Solution:
    def whichWeekDay(self, day):
        if day == 1:
            print('Monday')
        elif day == 2:
            print('Tuesday')
        elif day == 3:
            print('Wednesday')
        elif day == 4:
            print('Thursday')
        elif day == 5:
            print('Friday')
        elif day == 6:
            print('Saturday')
        elif day == 7:
            print('Sunday')
        else:
            print('Invalid')   

        #print(day)
```

## Problem Link
https://takeuforward.org/plus/dsa/problems/switch-case?source=strivers-a2z-dsa-track&subject=dsa&sidebar=open&tab=submissions

## Stats
- Success: true
- Test Cases: 11
- Time: 0.018s
- Memory: 9.12 KiB
