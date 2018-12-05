# Load Balancing algorithms

* load balancing improves the distribution of workloads across multiple computing resources.

* Optimize resource use 
* Maximize throughput (Maximize the production rate)
* Minimize response time
* Avoid overload of any single resource.

Hello Computer SCIENCE CLASS

![LB1](/assets/LB1.png)

# Round Robin
* Equally distribute to every server.
* Ignore the actual number of connection and the current system load

# Random
* Randomly pick one, the result will close to round robin when the number of uses increase.

# Weight Round Robin
* Consider the differences of each server, the algorism set a weight to each server, the powerful and      low load will receives a higher weight; the high load receive a lower weight. The higher weight will
    have larger chance to receive a new mission. 

# Least Connection
* Pick the server that have the minimum number of connections.


