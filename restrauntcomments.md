While ordering food items in EatSure reading the comments related to the food might be essenestial in making a descision about actually ordering food.
Trie or Radix tree is useful in this case since itfacilitates efficient storage and retrieval of comments based on keywords or phrases. This structure supports fast lookups for comments containing specific terms (food item,quality etc.,).

In an online food ordering app, radix trees (or prefix trees) can efficiently manage and search user comments. By organizing comments based on their prefixes, radix trees enable quick retrieval of comments that share common words or phrases, enhancing search functionality. For example, when a user searches for reviews mentioning "delicious pizza," the radix tree swiftly narrows down to nodes matching these terms, providing relevant results. This structure supports auto-completion and spelling correction, improving user experience by facilitating fast and accurate comment searches, ultimately aiding users in making informed ordering decisions.

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
