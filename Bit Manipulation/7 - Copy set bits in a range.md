# Copy set bits in a range

Difficulty Level : Easy

Given two numbers X and Y, and a range [L, R] where 1 <= L <= R <= 32. You have to copy the set bits of 'Y' in the range L to R in 'X'. Return this modified X.

Note: Range count will be from Right to Left & start from 1.

**Examples :**

```
Input: 
X = 44, Y = 3 
L = 1,  R = 5
Output: 
47
Explaination: 
Binary represenation of 44 and 3 is 101100 and 000011. So in the range 1 to 5 there are two set bits of 3 (1st & 2nd position). If those are set in 44 it will become 101111 which is 47.
```

Links:

[Copy set bits in a range](https://www.geeksforgeeks.org/problems/copy-set-bits-in-range0623/1?itm_source=geeksforgeeks&itm_medium=article&itm_campaign=practice_card)