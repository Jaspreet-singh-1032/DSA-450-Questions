# Find shortest unique prefix for every word in a given list

Difficulty Level : Medium

You are given an array containing ‘N’ words. For each word, you need to find its shortest prefix which can uniquely identify it. For example “abcd” and “abdc” both have the prefix “ab” in common so we can’t uniquely find a word using the prefix “ab”. To uniquely identify both the words we need the prefix “abc” from “abcd” and “abd” from “abdc”.

Note:
You can assume that the words are unique. It means that it is always possible to find a unique prefix for each word.

**Examples :**

```
Input:
2
2
abcd
acdb
3
many
mango
mad
Output:
ab
ac
many
mang
mad
Explanation:
Test case 1:
The string “abcd” and “acbd” have a common prefix “a” which can’t be used as a unique prefix so to make a unique prefix we will add one more character to “a” from each word. The “ab” for “abcd” and prefix “ac” for “acbd” is now the shortest and unique prefix.
Test case 2:
For string “many” the prefix “m” and “ma” is common in“mango” and “mad”. Similarly “man” is again common in “mango”. “Many” itself will be the unique shortest prefix.

For string “mango” we have the string ”many” such that “man” is common in both of them so for “mango” the prefix “mang” will the unique shorted prefix.

For string “mad” we have strings “many” and “mango” such that   “ma” is common in all of them. “Mad” itself will be a unique shortest prefix.
```

Links:

[Find shortest unique prefix for every word in a given list](https://www.naukri.com/code360/problems/shortest-unique-prefix_1094887?topList=love-babbar-dsa-sheet-problems&utm_source=website&utm_medium=affiliate&utm_campaign=450dsatracker)