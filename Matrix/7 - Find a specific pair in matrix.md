# Find a specific pair in matrix

Difficulty Level : Medium

You have been given a 2-D matrix ‘MAT’ of size ‘N’ x ‘N’ i.e. N rows and N columns. Your task is to find the maximum value of ‘MAT[a][b]’ - ‘MAT[c][d]’ over all possible indices (0 <= ‘a’, ‘b’, ‘c’, ‘d’ < ‘N’) such that . ‘a’ > ‘c’ and ‘b’ > ‘d’.

For example:

In this example, to maximise the value of ‘MAT[a][b]’ - ‘MAT[c][d]’ fulfilling the given conditions on indices (‘a’ > ‘c’ and ‘b’ > ‘d’), we take ‘a’ = 2, ‘b’ = 2, ‘c’ = 0 and ‘d’ = 0 .  So, ‘MAT[a][b]’ = 9 and ‘MAT[c][d]’ = 1 and the value of ‘MAT[a][b]’ - ‘MAT[c][d]’ => 9 - 1 = 8 which is maximum among all possible combinations.

**Examples :**

```
Input:
2
3
1 2 3
4 5 6
7 8 9
3
-1 -2 -3
-4 -5 -6
-7 -8 -9
Output:
8
-4
```

Links:

[Find a specific pair in matrix](https://www.naukri.com/code360/problems/find-a-specific-pair-in-the-matrix_1115467?topList=love-babbar-dsa-sheet-problems&utm_source=website&utm_medium=affiliate&utm_campaign=450dsatracker)