# Water Connection Problem

Difficulty Level : Hard

There are n houses and p water pipes in Geek Colony. Every house has at most one pipe going into it and at most one pipe going out of it. Geek needs to install pairs of tanks and taps in the colony according to the following guidelines.  
1. Every house with one outgoing pipe but no incoming pipe gets a tank on its roof.
2. Every house with only one incoming and no outgoing pipe gets a tap.
The Geek council has proposed a network of pipes where connections are denoted by three input values: ai, bi, di denoting the pipe of diameter di from house ai to house bi.
Find a more efficient way for the construction of this network of pipes. Minimize the diameter of pipes wherever possible.
Note: The generated output will have the following format. The first line will contain t, denoting the total number of pairs of tanks and taps installed. The next t lines contain three integers each: house number of tank, house number of tap, and the minimum diameter of pipe between them.

**Examples :**

```
Input:
n = 9, p = 6
a[] = {7,5,4,2,9,3}
b[] = {4,9,6,8,7,1}
d[] = {98,72,10,22,17,66} 
Output: 
3
2 8 22
3 1 66
5 6 10
Explanation:
Connected components are 
3->1, 5->9->7->4->6 and 2->8.
Therefore, our answer is 3 
followed by 2 8 22, 3 1 66, 5 6 10.
```

Links:

[Water Connection Problem](https://www.geeksforgeeks.org/problems/water-connection-problem5822/1)