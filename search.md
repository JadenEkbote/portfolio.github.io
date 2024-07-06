## Searching food items in EatSure.
Searching food items in an online food ordering app may involve much more than just searching and finding a food item. The app should display all the resutrants which have the said query based on the relevancy to the user, the most rasted and many such more factors.

### Algorithms Used:
- **Trie/prefix tree**: A trie, also known as a prefix tree, is a data structure that stores strings in a hierarchical way. Each node in a trie represents a character or a prefix of a string, and each edge connects a node to its children nodes that share the same prefix [[2](https://www.linkedin.com/advice/1/what-distinguishes-trie-from-radix-tree-skills-programming-kamdc#:~:text=A%20trie%20is%20a%20tree,have%20nodes%20with%20multiple%20characters.)]
  
![trietree](https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/5f16f5d4-fe90-4b0e-9fa7-39faefc9aae8)

The above image shows the structure of the trie trees. However, Trie trees can store redundant information as the same prefix might be stored multiple times. Hence, we go for a radix tree.

- **Radix Tree**: a radix tree (also radix trie or compact prefix tree or compressed trie) is a data structure that represents a space-optimized trie (prefix tree) in which each node that is the only child is merged with its parent. The result is that the number of children of every internal node is at most the radix r of the radix tree, where r is a positive integer and a power x of 2, having x ≥ 1.[[3](https://jtkyaw.medium.com/radix-tree-data-structure-640211ad3935)]

### Time Complexity Analysis:

| Algorithm | Time complexity |
|----------|----------|
| Trie/Prefix Trees   | O(n*d)  | 
| Radix Trees   | O(N * avgL)  | 
