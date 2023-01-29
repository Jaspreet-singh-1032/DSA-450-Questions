# Minimum no. of Jumps to reach end of an array

Difficulty Level : Hard

Given an array of integers where each element represents the max number of steps that can be made forward from that element. Write a function to return the minimum number of jumps to reach the end of the array (starting from the first element). If an element is 0, then we cannot move through that element. If we can’t reach the end, return -1.

***Example 1:***
```
Input:  arr[] = {1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9}
Output: 3 (1-> 3 -> 8 -> 9)
 
Explanation: Jump from 1st element to 
2nd element as there is only 1 step, 
now there are three options 5, 8 or 9. 
If 8 or 9 is chosen then the end node 9 
can be reached. So 3 jumps are made.
Input  :  arr[] = {1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1}
Output : 10

Explanation: In every step a jump is 
needed so the count of jumps is 10.
```

***Example 2:***
```
Input: nums = [2,3,1,1,4]
Output: 2
Explanation: The minimum number of jumps to reach the last index is 2. Jump 1 step from index 0 to 1, then 3 steps to the last index.
```

Links:
- [Minimum number of jumps to reach end - GFG](https://www.geeksforgeeks.org/minimum-number-jumps-reach-endset-2on-solution/)
- [Minimum number of jumps to reach end - Leetcode](https://leetcode.com/problems/jump-game-ii/)
