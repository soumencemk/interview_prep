# Eventually consistent
"Eventually consistent" refers to a consistency model used in distributed computing systems, particularly in distributed databases and other data storage systems. In an eventually consistent system, updates made to data replicas in different parts of the system are not immediately propagated to all replicas. Instead, there is a delay or latency in the synchronization process, and it's possible for different replicas to temporarily diverge from each other.

However, the eventual consistency model guarantees that, given enough time and assuming no further updates, all replicas will eventually converge to the same consistent state. In other words, while the system may exhibit temporary inconsistencies, these inconsistencies are resolved over time, leading to eventual convergence.

Key characteristics of eventually consistent systems include:

1. **Asynchronous updates**: Changes made to data in one part of the system are asynchronously propagated to other replicas. There is no immediate synchronization, so different replicas may have different views of the data for a period of time.

2. **Loose consistency guarantees**: Unlike systems with strong consistency models (such as ACID databases), eventually consistent systems provide weaker consistency guarantees. They prioritize availability and partition tolerance over strict consistency, which allows them to continue functioning even in the face of network partitions or failures.

3. **Eventual convergence**: Despite temporary inconsistencies, eventually consistent systems ensure that all replicas will converge to the same consistent state over time. This convergence is achieved through background processes that reconcile differences between replicas and propagate updates to ensure consistency.

Eventual consistency is commonly used in distributed systems where achieving strong consistency in real-time across all replicas is either impractical or unnecessary due to factors like scale, latency, or the nature of the application. It allows systems to remain available and responsive even in the presence of network partitions or failures, while still ensuring that data consistency is eventually achieved.