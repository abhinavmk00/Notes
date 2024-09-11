![[Pasted image 20240911215822.png]]
##### Description:

In a ring topology, each node is connected to exactly two other nodes, forming a circular data path. Data travels in one direction (unidirectional) or both directions (bidirectional) around the ring.

##### Advantages:

- **Predictable Performance:** Data transmission is typically faster and more predictable since each node has a dedicated path.
- **Easy to Troubleshoot:** Faults are easier to locate because the network will fail in a specific part of the ring.
- **Collisions Are Minimal:** As data travels in one direction, the risk of collisions is reduced compared to bus topology.

##### Disadvantages:

- **Single Point of Failure:** If one node or connection fails, it can disrupt the entire network unless a redundant path is provided.
- **Difficult to Expand:** Adding or removing nodes requires the network to be temporarily disconnected, which can be disruptive.
- **Maintenance Complexity:** Upgrading or changing the network requires careful coordination to avoid downtime.

