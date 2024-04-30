# Write a program to Delete loop in a linked list.		

Difficulty Level : Medium

Given a linked list of N nodes such that it may contain a loop.

A loop here means that the last node of the link list is connected to the node at position X(1-based index). If the link list does not have any loop, X=0.

Remove the loop from the linked list, if it is present, i.e. unlink the last node which is forming the loop.

**Examples :**

```
Input:
N = 3
value[] = {1,3,4}
X = 2
Output: 1
Explanation: The link list looks like
1 -> 3 -> 4
     ^    |
     |____|    

Input:
N = 4
value[] = {1,8,3,4}
X = 0
Output: 1
Explanation: The Linked list does not 
contains any loop
```

Links:

[detect-and-remove-loop-in-a-linked-list](https://www.geeksforgeeks.org/detect-and-remove-loop-in-a-linked-list/)
