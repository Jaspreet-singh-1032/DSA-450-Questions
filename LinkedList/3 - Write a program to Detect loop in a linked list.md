# Write a program to Detect loop in a linked list.	

Difficulty Level : Easy

Given the head of a singly linked list, the task is to check if the linked list has a loop. A loop means that the last node of the linked list is connected back to a node in the same list.  So if the next of the last node is null. then there is no loop.

Note: You need to return a boolean value true if there is a loop, otherwise false.

The following is an internal representation of every test case (three inputs).
A LinkedList and a pos (1-based index)-Position of the node to which the last node links back if there is a loop. If the linked list does not have any loop, then pos = 0.

**Examples :**

```
Input: LinkedList: 1->3->4, pos = 2
Output: true 1->3->4->3
Explanation: 
See the above list there exists a loop connecting the last node back to the second node.
```

Links:

[detect-loop-in-a-linked-list](https://www.geeksforgeeks.org/problems/detect-loop-in-linked-list/1?itm_source=geeksforgeeks&itm_medium=article&itm_campaign=practice_card)
