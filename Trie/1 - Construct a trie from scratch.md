# Construct a trie from scratch

Difficulty Level : Hard

Implement Trie Data Structure to support these operations:

insert(word) - To insert a string "word" in Trie
search(word) - To check if string "word" is present in Trie or not.
startsWith(word) - To check if there is any string in the Trie that starts with the given prefix string "word".


Three type of queries denote these operations:

Type 1: To insert a string "word" in Trie.
1 word

Type 2: To check if the string "word" is present in Trie or not.
2 word

Type 3: To check if there is any string in the Trie that starts with the given prefix string "word".
3 word

**Examples :**

```
Input:
5
1 hello
1 help
2 help
3 hel
2 hel 
Output:
true
true
false
Explanation :
Query 1: "hello" is inserted
Query 2: "help" is inserted
Query 3: "true" is printed as "help" is present
Query 4: "true" is printed as "hello" and "help" is present having the prefix "hel"
Query 5: "false" is printed as "hel" is not present
```

Links:

[Construct a trie from scratch](https://www.naukri.com/code360/problems/implement-trie_631356?topList=love-babbar-dsa-sheet-problems&utm_source=website&utm_medium=affiliate&utm_campaign=450dsatracker)