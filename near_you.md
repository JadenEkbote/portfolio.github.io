Finding Restraunts near you is one Problem EatSure faces as it has to involve geographical statictics and coordinates into Picture.

k-d tree (short for k-dimensional tree) is a space-partitioning data structure for organizing points in a k-dimensional space. K-dimensional is that which concerns exactly k orthogonal axes or a space of any number of dimensions. k-d trees are a useful data structure for several applications, such as:

Searches involving a multidimensional search key (e.g. range searches and nearest neighbor searches) &
Creating point clouds.
k-d trees are a special case of binary space partitioning trees.

For geospatial restaurant detection, k-d trees are effective due to their efficient organization of spatial data, enabling rapid querying and proximity searches. By recursively partitioning the data space into nested half-spaces, k-d trees allow for quick location-based queries and nearest neighbor searches, which are essential for identifying nearby restaurants within a given range. Their adaptability to multidimensional data, such as coordinates, ensures optimal performance in handling large datasets, making them a robust choice for applications in geographic information systems (GIS) and location-based services.


![ktree_1](https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/25936982-00b3-49bb-9ee3-b546afbab581)


### Time complexity: O(log n) for insertion and O(n) for range, where n is the number of elements.

### Space Complexity:  O(n), where n is the number of elements.

[click here](https://github.com/JadenEkbote/DSA/blob/main/trees/kdtree.c), for the implementation of K-Dimensional tree.
