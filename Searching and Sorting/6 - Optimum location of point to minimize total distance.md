# Optimum location of point to minimize total distance

Difficulty Level : Hard

You are given a straight line on a 2D plane in the form of (ax + by + c = 0) and an array of points of the form (Xi, Yi). Your task is to find a point on the given line for which the sum of distances from this point to the given array/list of points is minimum.

For Example :

Here the equation for the given line is x - y = 0, i.e. a = 1, b = -1 and c = 0. 
There are two points, i.e. (-1, 1) and (1, -1).

So, the point on the line that has minimum distances from the points is (0, 0). The sum of distances is sqrt(1 + 1) + sqrt(1 + 1) = sqrt(2) + sqrt(2) = 2.83 (rounding to 2 decimal digits).

**Examples :**

```
Input:
2
3 2 5
5
1 -1
2 3
4 4
5 -1
3 2
3 1 -4
4
1 2
4 -2
5 -3
7 -6
Output:
24.94
15.32
```

Links:

[Optimum location of point to minimize total distance](https://www.naukri.com/code360/problems/optimum-location_1116097?topList=love-babbar-dsa-sheet-problems&utm_source=website&utm_medium=affiliate&utm_campaign=450dsatracker)