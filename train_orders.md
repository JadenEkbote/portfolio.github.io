One of the most advertised faeture nowdays is ordering the food via the app while sitting in the train 
and it being hand delievred to you at the station when the train arrvies. 
While it may the physical constraints of the train arrival time and ordering the food in advance, 
it uses few pathfinding algortihms to find the best path from the station to resutrant for the delivery partner and making sure he delivers it.


Dijkstra's algorithm is a fundamental algorithm in computer science designed to find the shortest paths between nodes in a weighted graph, where the weights are non-negative. Conceived by Edsger W. Dijkstra in 1956 and published in 1959, it operates by iteratively selecting the node with the smallest known distance from the starting node, and exploring all its adjacent nodes. Initially, the distance to the starting node is set to zero and all other nodes are set to infinity. The algorithm updates the shortest distance to each node from the starting node and continues this process until all nodes have been visited or the shortest path to the target node is determined. This approach ensures that the shortest path from the starting node to any other node is found efficiently.

![cse-to-bag-final](https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/64511d5a-af4f-49e9-9b94-6e5806ee1cb8)

### Time Complexity: O(V^2), Where V is the number of vertices.

### Space Complexity: O(E + V), where V is the number of vertices and E is the number of edges in the graph.

[click here](https://github.com/JadenEkbote/DSA/blob/main/trees/dijkistras.c), for the implementation of dijkistras.
