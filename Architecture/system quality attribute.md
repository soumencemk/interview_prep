# system quality attribute

**System quality attributes**, often referred to as non-functional requirements, complement functional requirements in shaping a system's architecture and design. They define characteristics centering around reliability, maintainability, and other performance aspects.

Developers aim to ensure these attributes right from the conceptual stages, thus they shape the software's foundation and guide architectural decision-making throughout the development cycle.

### Common System Quality Attributes

1. **Performance**: Describes the system's responsiveness, throughput, and resource consumption levels, typically under specific conditions. For instance, the system might need to perform optimally when handling a large number of concurrent users or a heavy workload.

2. **Reliability**: Refers to the system's ability to perform consistently and accurately, without unexpected failures. Systems with high reliability often integrate fault tolerance mechanisms and have a defined recovery strategy in place, like data backups or redundant components.

3. **Availability**: This attribute specifies the system's uptime and accessibility. It's often expressed as a percentage of time the system is expected to be operational. For example, "99.99% uptime."

4. **Security**: A mandatory system attribute that addresses the protection of data and resources from unauthorized access, breaches, or corruption. It is vital for systems where data confidentiality, integrity, and availability are paramount.

5. **Maintainability**: Represents a system's ease of maintaining or modifying its components. It focuses on the efficiency of repairs, upgrades, and adaptions. Key metrics include time for updates, code complexity post-changes, and number of errors after a modification.

6. **Portability**: Defines a system's adaptability to run across different environments, such as diverse hardware, operating systems, or cloud providers. A more portable system is generally preferred as it offers flexibility and future-proofing.

7. **Scalability**: Refers to the system's ability to accommodate growing workloads. It might be realized through vertical scaling (upgrading hardware) or horizontal scaling (adding more instances). 

8. **Usability**: Emphasizes the system's ease of use and intuitive operation, catering to user experience aspects.

9. **Interoperability**: Describes a system's capability to communicate and share data with other systems or components, and its compatibility with different technologies.

10. **Testability**: The degree to which a system facilitates the generation of test cases and testing processes.

11. **Flexibility**: Represents the system's capacity to adapt to new situations through customization.

### Key Performance Indicators

Each quality attribute can measure its adherence, typically using quantitative metrics or key performance indicators (KPIs):

- **Performance**: Utilization metrics, response times, and throughput.
- **Reliability**: Measured often in uptime percentages.
- **Availability**: Can be measured using uptime metrics, such as "five nines" (99.999%).
- **Security**: Can be evaluated using penetration testing results, compliance indicators, security frameworks adhered to, and specific security protocols' success rates.

###  Architectural Decisions

Architectural patterns and styles, as well as design strategies, are thoroughly informed by quality attributes, ensuring that the completed software system best meets its operational goals.

For instance, a system focusing on high availability like a cloud-based ERP might adopt a microservices architecture and utilize load balancers and auto-scaling clusters.

In contrast, a system that requires high reliability, such as a medical equipment monitoring system, might employ a modular architecture with strict data consistency mechanisms and undergo stringent testing procedures.