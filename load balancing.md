Managing huge coustmer traffic during sales by EatSure can be acheived thorugh laodbalancing.

Load balancing is a critical technique for managing high customer traffic during sales events on EatSure. It involves distributing incoming requests across multiple servers to ensure no single server becomes overwhelmed, thereby maintaining high availability and performance. During sales events, when traffic spikes are common, effective load balancing ensures that users experience minimal latency and maximum reliability. The primary goals are to balance the load evenly, prevent server overloads, and optimize resource utilization.

### Greedy Approach
The greedy approach to load balancing involves dynamically distributing requests to the server that appears to be the least loaded at the moment of each request. This method operates on real-time information about server loads, making immediate decisions that aim to minimize the current maximum load across all servers. For instance, if EatSure experiences a surge in traffic during a flash sale, the load balancer will direct each incoming user request to the server with the current lowest load.
