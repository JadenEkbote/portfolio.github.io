Tracking your food order in real time when the dleivery partner is delivering it to your destination is one of the most important features that the online food delivery platform provides. A* search is one of the pathfinding algorithms that can be utilised for finding the shortest path between the delivery partner and the users destination.

The A* search algorithm is an algorithm that focuses on optimal pathfinding, using heuristic evaluation and cost-effective analysis. Combining elements of graph theory and computational intelligence, A* navigates the whole structre by prioritizing nodes based on a blend of heuristic estimates and past cost metrics, ensuring minimal computational overhead while maximizing solution accuracy.

The evaluation function, f(x), for the A* search algorithm is the following:

f(x) = g(x) + h(x)
Where g(x) represents the cost to get to node x and h(x) represents the estimated cost to arrive at the goal node from node x. For the algorithm to generate the correct result, the evaluation function must be admissible, meaning that it never overestimates the cost to arrive at the goal node.

The A* algorithm is implemented in a similar way to Dijkstra’s algorithm. Given a weighted graph with non-negative edge weights, to find the lowest-cost path from a start node S to a goal node G, two lists are used:
- An open list, implemented as a priority queue, which stores the next nodes to be explored. Because this is a priority queue, the most promising candidate node (the one with the lowest value from the evaluation function) is always at the top. Initially, the only node in this list is the start node S.
-A closed list which stores the nodes that have already been evaluated. When a node is in the closed list, it means that the lowest-cost path to that node has been found.

To find the lowest cost path, a search tree is constructed in the following way:

-Initialize a tree with the root node being the start node S.
-Remove the top node from the open list for exploration.
-Add the current node to the closed list.
-Add all nodes that have an incoming edge from the current node as child nodes in the tree.
-Update the lowest cost to reach the child node.

-Compute the evaluation function for every child node and add them to the open list.
-Just like in Dijkstra’s algorithm, the lowest cost is updated as the algorithm progresses in the following way:

current_lowest_cost = min(current_lowest_cost, parent_node_cost + edge_weight)

<img width="763" alt="a*search" src="https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/cfb968de-a65c-4f02-839e-301aa7049ee4">
