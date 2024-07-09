## Searching food items in EatSure.
Searching food items in an online food ordering app may involve much more than just searching and finding a food item. The app should display all the resutrants which have the said query based on the relevancy to the user, the most rated and many such more factors.

### Algorithms Used:
- **Trie/prefix tree**: A trie, also known as a prefix tree, is a data structure that stores strings in a hierarchical way. Each node in a trie represents a character or a prefix of a string, and each edge connects a node to its children nodes that share the same prefix [[2](https://www.linkedin.com/advice/1/what-distinguishes-trie-from-radix-tree-skills-programming-kamdc#:~:text=A%20trie%20is%20a%20tree,have%20nodes%20with%20multiple%20characters.)]
  
![trietree-2](https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/bbb4a742-ee50-43fa-8551-1e7823a1bb04)


The above image shows the structure of the trie trees. However, Trie trees can store redundant information as the same prefix might be stored multiple times. Hence, we go for a radix tree.

- **Radix Tree**: a radix tree (also radix trie or compact prefix tree or compressed trie) is a data structure that represents a space-optimized trie (prefix tree) in which each node that is the only child is merged with its parent. The result is that the number of children of every internal node is at most the radix r of the radix tree, where r is a positive integer and a power x of 2, having x ≥ 1.[[3](https://jtkyaw.medium.com/radix-tree-data-structure-640211ad3935)]
  

<img width="568" alt="Screenshot 2024-07-09 at 9 04 35 AM" src="https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/e759ff4d-0ab0-47e3-b0e2-594e3865fda8">


### Time & space Complexity Analysis:



| Algorithm | Time complexity |
|----------|----------|
| Trie/Prefix Trees (Search)  | O(N * avgL), where 'N' is the number of strings we want to insert in Trie and 'avgL' is the average length of 'N' strings | 
| Radix Trees (Search)  | O(n)  | 


| Algorithm | Space complexity |
|----------|----------|
| Trie/Prefix Trees (Search)  | O(alphabet_size * average key length * N) | 
| Radix Trees (Search)  | O(N), where N is the total number of characters in all the stored strings.  | 

[Click Here](https://github.com/JadenEkbote/DSA/blob/main/trees/radix_trees.cpp), For the implmentation of radix tree.
