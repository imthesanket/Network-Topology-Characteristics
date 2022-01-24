# Network Topology Characteristics

The network topology properties can be measured in many different criteria. The systematical study of network topology characteristics is meaningful in graph data mining and temporal‐spatial analysis and prediction in dynamic complex network systems.

## Popular topology properties:

### Centrality

* Node centrality (node degree distribution and node weight degree distribution).
* Edge (betweenness) centrality: the fraction of all shortest paths that pass through a node.
* Page rank centrality: the number of times that a node will be visited on a sufficiently long random walk on the graph.
* Closeness Centrality: the efficiency of the information propagation from one node to the other nodes. It measures how long it will take information to spread from a given vertex to other reachable vertices in the network.
* Information Centrality: nodes’ influence on the network efficiency of information propagation. The information centrality of a vertex i is defined as the relative drop in the network efficiency caused by the removal from G of the edges incident with v. 

### Path Length

* Average shortest path length from a node to all other nodes. It relates to the routing hops.
* Diameter: longest of the shortest paths between all pairs of nodes.
* Effective diameter: path length that defines the 90th percentile of all paths.

### Community Structure

* Clustering coefficient: the number of edges among the neighbors of a node as compared to the maximum possible numbers. The clustering coefficient is related to the resilience of the routing infrastructure because it reflects the number of alternative route between pairs of nodes.
* Degree assortativity measures whether nodes tend to connect others of similar degree.
* K-cores decomposition measures successive maximally connected subgraphs.
* Structural centrality: hierarchy from the most influential nodes to least influential nodes.

### Scale-free Structure

* Check whether the degree distribution follows the power-law distribution.
* Small-world network versus scale-free network.
