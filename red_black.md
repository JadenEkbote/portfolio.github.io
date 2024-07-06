Each Restuarnt will have its own menu and all the ratings for the menu with it. 
The ability to sort menu items based on their type, or the ratings of the resturant are maintained using Red-black trees.

Binary search trees are a fundamental data structure, but their performance can suffer if the tree becomes unbalanced. Red Black Trees are a type of balanced binary search tree that use a set of rules to maintain balance, ensuring logarithmic time complexity for operations like insertion, deletion, and searching, regardless of the initial shape of the tree. Red Black Trees are self-balancing, using a simple color-coding scheme to adjust the tree after each modification.[[6](https://www.geeksforgeeks.org/introduction-to-red-black-tree/)]

Whenever the user filters or sorts the menu the traversal is applied in the red-black tree that shows the sorted list of menu items and every time a rating changes the red-black tree updates the nodes, the instertion and deletion of menu items can also be maintained using red black tree so that it provides a balanaced tree at the end.

![Red black tree](https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/4e96d7dd-2617-4457-83a4-46492880ecd9)
