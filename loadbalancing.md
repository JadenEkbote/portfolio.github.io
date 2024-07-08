Managing huge coustmer traffic during sales by EatSure can be acheived thorugh laodbalancing.

Load balancing is a critical technique for managing high customer traffic during sales events on EatSure. It involves distributing incoming requests across multiple servers to ensure no single server becomes overwhelmed, thereby maintaining high availability and performance. During sales events, when traffic spikes are common, effective load balancing ensures that users experience minimal latency and maximum reliability. The primary goals are to balance the load evenly, prevent server overloads, and optimize resource utilization.

### Greedy Approach
The greedy approach to load balancing involves dynamically distributing requests to the server that appears to be the least loaded at the moment of each request. This method operates on real-time information about server loads, making immediate decisions that aim to minimize the current maximum load across all servers. For instance, if EatSure experiences a surge in traffic during a flash sale, the load balancer will direct each incoming user request to the server with the current lowest load.

### Static Approach
The static approach to load balancing involves pre-determined distribution rules that do not change based on real-time server load. This can include methods such as round-robin, where each server is assigned requests in a fixed, cyclic order, or fixed-weight distribution, where requests are distributed based on predefined weights assigned to each server.

![346354869-72fbef9f-9e96-4f8b-926a-94c1055ec858](https://github.com/JadenEkbote/portfolio.github.io/assets/97228905/20de99c9-a9fa-41e1-9d54-79750f7e8fca)


Using round-robin or weighted distribution as the default method during regular operations will help in implementing real-time monitoring and a greedy load balancing layer that activates during high-traffic events, such as sales, to manage spikes effectively.

[click here](https://github.com/JadenEkbote/DSA/blob/main/trees/greedy.c), to find implementation of weighted round robin with a greedy approach.
