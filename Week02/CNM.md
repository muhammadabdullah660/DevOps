### Cloud Native Microservices

- "Cloud Native Microservices" refer to a software architecture approach that combines two key concepts: *Cloud native and Microservices*.
- **Cloud native** refers to designing and running applications that take full advantage of cloud computing infrastructure and platform services, such as containerization, automation, and scaling.
- **Microservices** are a software development approach where a large application is broken down into smaller, independent, and loosely coupled services that can be developed, deployed, and scaled independently. Each microservice performs a specific function and communicates with other microservices through APIs.
- Combining these two concepts, Cloud Native Microservices enable the development of highly scalable and resilient applications that can be easily deployed and managed in a cloud environment. 
- The *microservices architecture* allows for greater flexibility, faster development cycles, and easier maintenance, while the *cloud-native infrastructure* provides the necessary tools and services to manage and scale the microservices as needed.

### Key characteristics of Cloud Native Microservices

- **Containerization**: Cloud Native Microservices are typically packaged as containers, which allows for efficient deployment and scaling of services. Containers provide a lightweight and consistent environment for applications to run in.
- **API-based communication**: Microservices communicate with each other through APIs, which allows for loose coupling between services and promotes modularity. This also allows for greater flexibility in how services are deployed and managed.
- **Autonomous**: Microservices are designed to be autonomous and independent, with each service having its own data store and resources.
- **Resilience**: Cloud Native Microservices are designed to be resilient, with services able to handle failures and recover quickly.
- **DevOps**: Cloud Native Microservices are typically developed and deployed using DevOps practices, which promote collaboration between development and operations teams, and emphasize automation, continuous integration, and continuous delivery.
- **Scalability**: Microservices architecture allows for individual services to be scaled independently, which enables greater scalability and flexibility. This is achieved through techniques such as horizontal scaling and auto-scaling.
- **Observability  and Monitoring**: Cloud Native Microservices are designed with observability in mind, which means that services are instrumented with monitoring and logging tools to provide insights into the performance and behavior of the system.

### Designing for Failure in DevOps

- An approach used in DevOps which plans and prepares for failure in hardware, network or system failure
- The system is designed keeping in mind that there might be failure of any component at any time.
- So, we design the systems so that they can recover quickly from that failures.
- It ensures that applications and systems can continue to function even when things go wrong. 
- By anticipating potential failures and designing systems to handle them, organizations can minimize the impact of downtime and prevent service disruptions.

### Key Practices 

1. **Redundancy**: Implement multiple instances of components or services that can take over if one of them fails. Redundancy helps to ensure high availability and fault tolerance.
2. **Auto-scaling and self-healing**: Design systems that can automatically scale and adapt to changing demands and recover from failures. 
3. **Graceful degradation**: Design applications to handle failures in a way that minimizes the impact on end-users. By providing limited functionality or reduced performance during a failure, users can still access critical features while the issue is being resolved.
4. **Circuit breakers and timeouts**: Implement circuit breaker and timeout patterns to handle failures in external dependencies or services. 
5. **Monitoring and observability:** Implement monitoring and observability tools to detect failures quickly and understand their root causes. Metrics, logs, and traces are collected and analyzed to provide insights into the health and performance of the system, enabling faster issue resolution.
6. **Automate recovery:** Build automated recovery processes that can detect and respond to failures automatically, such as automatically restarting a failed service or migrating to a secondary server.
7. **Implement load balancing**: Use load balancing techniques to distribute traffic across multiple instances of services or applications, which can prevent overloading and mitigate the impact of failures.
8. **Practice chaos engineering**: Conduct controlled experiments to test the resilience of the system by introducing failure scenarios and measuring the response. This can help identify weaknesses in the system and improve its overall resilience.
