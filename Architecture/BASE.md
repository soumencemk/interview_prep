# BASE

The BASE property is an acronym that stands for Basically Available, Soft state, and Eventually consistent. It is used to describe the characteristics of certain distributed systems, particularly NoSQL databases, that prioritize availability and partition tolerance over strict consistency.

Here's what each part of the BASE property means:

1. **Basically Available**: This means that the system guarantees a basic level of availability, even in the face of network failures, partitions, or other kinds of failures. In other words, the system remains operational and responsive to client requests even under adverse conditions, although it may not provide full functionality or consistency.

2. **Soft state**: Soft state refers to the notion that the system's state may be transient and might change over time even without input. This allows for flexibility and eventual consistency within the system. Soft state is in contrast to the concept of "hard state," where the system's state remains unchanged until explicitly modified.

3. **Eventually consistent**: Eventually consistent means that, given a certain period of time and assuming no further updates, all replicas or copies of data within the system will eventually converge to the same state. In other words, while the system may not provide strong consistency guarantees at all times, it ensures that, over time, all replicas will become consistent.

The BASE property is often used to describe distributed systems where achieving strict consistency (as in ACID properties of traditional databases) across all nodes is either impractical or unnecessary due to factors like scale, latency, or the nature of the data being stored. Instead, these systems prioritize availability and partition tolerance while accepting some degree of inconsistency that will eventually be resolved.