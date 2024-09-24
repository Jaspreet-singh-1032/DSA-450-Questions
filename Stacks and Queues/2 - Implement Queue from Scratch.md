# Implement Queue from Scratch

Difficulty Level : Easy

Implement a Queue Data Structure specifically to store integer data using a Singly Linked List or an array.

You need to implement the following public functions :

1. Constructor: It initializes the data members as required.

2. enqueue(data): This function should take one argument of type integer. It enqueues the element into the queue.

3. dequeue(): It dequeues/removes the element from the front of the queue and in turn, returns the element being dequeued or removed. In case the queue is empty, it returns -1.

4. front(): It returns the element being kept at the front of the queue. In case the queue is empty, it returns -1.

5. isEmpty(): It returns a boolean value indicating whether the queue is empty or not.
Operations Performed on the Queue :
Query-1(Denoted by an integer 1): Enqueues integer data to the queue.

Query-2(Denoted by an integer 2): Dequeues the data kept at the front of the queue and returns it to the caller, return -1 if no element is present in the queue.

Query-3(Denoted by an integer 3): Fetches and returns the data being kept at the front of the queue but doesn't remove it, unlike the dequeue function, return -1 if no element is present in the queue.

Query-4(Denoted by an integer 4): Returns a boolean value denoting whether the queue is empty or not.

**Examples :**

```
Input:
1
7
1 17
1 23
1 11
2
2
2
2
Output:
17
23
11
-1
Explanation:
The first three queries are of enQueue, so we will push 17, 23, and 11 into the queue.

The next four queries are of deQueue, so we will starting removing elements from the queue, so the first element will be 17, then 23, and then 11. And after the third dequeue query, the queue is now empty so for the fourth query, we will return -1.
```

Links:

[Implement Queue from Scratch](https://www.naukri.com/code360/problems/queue-using-array-or-singly-linked-list_2099908?topList=love-babbar-dsa-sheet-problems&utm_source=website&utm_medium=affiliate&utm_campaign=450dsatracker)