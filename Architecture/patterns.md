A **Software Architectural Pattern** is a proven, structured solution to a recurring design problem. These patterns offer a blueprint for conceptualizing systems and addressing common challenges in software architecture. They provide a vocabulary for developers and ensure commonly-faced problems are solved in a consistent manner.

### Common Architectural Patterns

1. **Layers**: Segregates functionality based on roles like presentation, domain logic, and data access.
  
2. **MVC**: Divides an application into three interconnected components: Model, View, and Controller, each with specific responsibilities.
   
3. **REST**: Utilizes common HTTP verbs and status codes, along with stateless communication, for easy data transfer in client-server setups.
   
4. **Event-Driven**: Emphasizes communication through events, with publishers and subscribers decoupled from one another.
   
5. **Microkernel**: Centralizes core operations in a lightweight kernel, while other services can be dynamically loaded and interact via messaging.
   
6. **Microservices**: Distributes applications into small, independently deployable services that communicate via network calls.
   
7. **Space-Based**: Leverages a distributed data grid for data sharing and event-driven workflows.
   
8. **Client-Server**: Divides an application into client-side and server-side components, with the server providing resources or services.

9. **Peer-to-Peer** (P2P): Emphasizes equal share in roles for nodes, promoting decentralized communication and resources sharing.
   
10. **Domain-Driven Design** (DDD): Encourages close alignment between development and a domain model, integrating logic and data into one unit.

### Best Practices for Architectural Patterns

- **Understanding before Application**: Ensure you are truly solving a problem specific to your context, and not adopting a pattern prematurely or needlessly complicating your design.

- **Design Flexibility**: A good architecture allows for future changes and is not overly rigid or exhaustive without reason.

- **Code Reusability**: Aim to minimize duplication by design and code reuse strategies.

- **Separation of Concerns**: Each component should have a clear, singular role, and should need to understand as little as possible about the rest of the system.

- **Scalability**: The architecture should be able to scale with complexity, requirements, and user load.

- **Maintainability**: It should be relatively easy to debug, enhance, and maintain the system.

- **Security and Compliance**: Your architecture should account for security standards in your domain, including data protection laws and best practices.

- **Clear Communication**: Developers should share a consistent vocabulary to understand the architecture, especially when collaborating on the system.


### Real-World Examples

- **MVC**: It is widely used in web applications, where the model represents data, the view displays the data, and the controller handles user inputs.

- **Microservices**: This architecture is prevalent in cloud-based systems like Netflix and Amazon. Services are loosely coupled and focus on specific business functionalities.

- **Event-Driven**: Used in various applications like chat systems, stock trading platforms, and IoT solutions where real-time data processing is crucial.

- **Space-Based**: Apache Spark and other big data technologies often use it for stream and batch processing.

- **Client-Server**: Common in web and mobile applications, where the server serves as a centralized resource.

- **P2P**: Popular in file-sharing applications and some blockchain implementations like BitTorrent and Bitcoin.

- **DDD**: Many enterprise-level applications, CRM systems, and portfolio management tools leverage this model for a more domain-focused design approach.