# Zig-Zag traversal of a binary tree

Difficulty Level : Medium

Given a binary tree with n nodes. Find the zig-zag level order traversal of the binary tree.
In zig zag traversal starting from the first level go from left to right for odd-numbered levels and right to left for even-numbered levels.

**Examples :**

```
Input:
        1
      /   \
     2    3
    / \    /   \
   4   5 6   7
Output:
1 3 2 4 5 6 7
Explanation:
For level 1 going left to right, we get traversal as {1}.
For level 2 going right to left, we get traversal as {3,2}.
For level 3 going left to right, we get traversal as {4,5,6,7}.
Merging all this traversals in single array we get {1,3,2,4,5,6,7}
```

Links:

[Zig-Zag traversal of a binary tree](https://www.geeksforgeeks.org/problems/zigzag-tree-traversal/1)
