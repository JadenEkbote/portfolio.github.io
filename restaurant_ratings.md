Managing restaurant ratings and updating them in real time for EatSure presents significant challenges due to the high volume and frequency of user interactions. The system must handle continuous updation of ratings, often from thousands of users simultaneously, without compromising performance. Ensuring that ratings are accurately aggregated and updated in real time requires efficient data structures and algorithms. Delays or inaccuracies in updates can lead to user dissatisfaction and unreliable recommendations. The complexity increases with the need for real-time calculations of averages and rankings.

Fenwick Trees can be used to solve this problem. A Fenwick tree or binary indexed tree (BIT) is a data structure that can efficiently update values and calculate prefix sums in an array of values. When compared with a flat array of values, the Fenwick tree achieves a much better balance between two operations: value update and prefix sum calculation. A flat array of _n_ values can either store the values or the prefix sums. In the first case, computing prefix sums requires linear time; in the second case, updating the array values requires linear time (in both cases, the other operation can be performed in constant time). Fenwick trees allow both operations to be performed in  _O(logn)_ time. This is achieved by representing the values as a tree with _n+1_ nodes where the value of each node in the tree is the prefix sum of the array from the index of the parent (inclusive) up to the index of the node (exclusive). The tree itself is implicit and can be stored as an array of _n_ values, with the implicit root node omitted from the array. The tree structure allows the operations of value retrieval, value update, prefix sum, and range sum to be performed using only  _O(log n)_ node accesses.

![BITSum](https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/f0cbfe34-eafe-4ac1-a87c-27d459f4c0d9)

### Time Complexity: O(log n) for query and update opertaions, O(n) for intilisation.

### Space Complexity: O(n).

[click here](https://github.com/JadenEkbote/DSA/blob/main/trees/fenwick.c), to find implemnetation of fenwick tree.
