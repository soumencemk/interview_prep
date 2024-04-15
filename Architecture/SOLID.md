# SOLID

SOLID is an acronym referring to a set of five design principles in object-oriented programming intended to make software designs more understandable, flexible, and maintainable. Each letter in SOLID stands for one of these principles:

1. **S - Single Responsibility Principle (SRP)**:
   - A class should have only one reason to change, meaning it should have only one responsibility.
   - This principle encourages dividing a system into smaller, more manageable parts, each responsible for a single aspect of functionality.

2. **O - Open/Closed Principle (OCP)**:
   - Software entities (classes, modules, functions, etc.) should be open for extension but closed for modification.
   - This principle encourages designing systems that can be extended with new functionality without modifying existing code, thus minimizing the risk of introducing bugs.

3. **L - Liskov Substitution Principle (LSP)**:
   - Subtypes should be substitutable for their base types without altering the correctness of the program.
   - In other words, objects of a superclass should be replaceable with objects of its subclasses without affecting the behavior of the program.

4. **I - Interface Segregation Principle (ISP)**:
   - Clients should not be forced to depend on interfaces they do not use.
   - This principle encourages breaking interfaces into smaller, more specific ones tailored to the needs of the clients that use them, thus avoiding unnecessary dependencies.

5. **D - Dependency Inversion Principle (DIP)**:
   - High-level modules should not depend on low-level modules. Both should depend on abstractions.
   - Abstractions should not depend on details. Details should depend on abstractions.
   - This principle promotes decoupling between modules by introducing abstractions/interfaces that define the interaction between them, rather than having them depend directly on each other.

Together, these principles help developers create software that is easier to understand, maintain, and extend over time. They promote good design practices such as separation of concerns, modularity, and flexibility.