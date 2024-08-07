Order tracking is one of the most important ascept in Online food delviery systems. In order tracking, estiamted time before the delivery plays a key role. Segment trees are data structures that are efficient at handling range query problems such as the meal prepration time by the restraunt, estimated delivery time, road conditions, weather conditions etc., hence, using segment trees we can provide real time data to the use.


A Segment Tree is a data structure that stores information about array intervals as a tree. This allows answering range queries over an array efficiently, while still being flexible enough to allow quick modification of the array. This includes finding the sum of consecutive array elements  _a[l......r]_ , or finding the minimum element in a such a range in  _O(log n)_  time. Between answering such queries, the Segment Tree allows modifying the array by replacing one element, or even changing the elements of a whole subsegment (e.g. assigning all elements  _a[l......r]_ to any value, or adding a value to all element in the subsegment).

In general, a Segment Tree is a very flexible data structure, and a huge number of problems can be solved with it. Additionally, it is also possible to apply more complex operations and answer more complex queries (see Advanced versions of Segment Trees). In particular the Segment Tree can be easily generalized to larger dimensions. For instance, with a two-dimensional Segment Tree you can answer sum or minimum queries over some subrectangle of a given matrix in only  _O(log^2 n)_ time.[[8](https://cp-algorithms.com/data_structures/segment_tree.html)]

One important property of Segment Trees is that they require only a linear amount of memory. The standard Segment Tree requires  _4n_  vertices for working on an array of size  _n_.\

Segment tree structure:

<img width="452" alt="Screenshot 2024-07-07 at 3 39 39 PM" src="https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/e4318ace-6260-43a9-bb7a-b5bbf881f69c">

### Time Complexity (Range Query): O(logn)

### Space Complexity (Range Query): O(n)

Click here, for implementation of segment tree for range query.
