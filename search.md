## Searching food items in EatSure.
Searching food items in an online food ordering app may involve much more than just searching and finding a food item. The app should display all the resutrants which have the said query based on the relevancy to the user, the most rasted and many such more factors.

### Algorithms Used:
- **Trie/prefix tree**: A trie, also known as a prefix tree, is a data structure that stores strings in a hierarchical way. Each node in a trie represents a character or a prefix of a string, and each edge connects a node to its children nodes that share the same prefix [[2](https://www.linkedin.com/advice/1/what-distinguishes-trie-from-radix-tree-skills-programming-kamdc#:~:text=A%20trie%20is%20a%20tree,have%20nodes%20with%20multiple%20characters.)]
- **Radix Tree**: Provides efficient indexing and fast lookup for video titles, descriptions, and tags. This data structure supports quick searches and autocomplete functionality by storing each character of the search terms in nodes.
- **A * with priority queue**: Ranks search results based on relevance. This algorithm considers multiple factors such as title matches, view count, likes, and user engagement to deliver the most pertinent results to the user.
