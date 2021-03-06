# Architecture

- From developer to architect (short videos): [https://www.developertoarchitect.com/lessons/](https://www.developertoarchitect.com/lessons/)

- Software Architecture Patterns (free PDF): [http://www.oreilly.com/programming/free/files/software-architecture-patterns.pdf](http://www.oreilly.com/programming/free/files/software-architecture-patterns.pdf)

- Microservices AntiPatterns and Pitfalls (free PDF): [https://www.oreilly.com/programming/free/files/microservices-antipatterns-and-pitfalls.pdf](https://www.oreilly.com/programming/free/files/microservices-antipatterns-and-pitfalls.pdf)

- Microservices vs. Service-Oriented Architecture (free PDF): [https://www.oreilly.com/programming/free/files/microservices-vs-service-oriented-architecture.pdf](https://www.oreilly.com/programming/free/files/microservices-vs-service-oriented-architecture.pdf)

- Microservices Patterns (book): [https://www.manning.com/books/microservices-patterns?a_aid=microservices-patterns-chris](https://www.manning.com/books/microservices-patterns?a_aid=microservices-patterns-chris)

- Microservices in Action (book): [https://www.manning.com/books/microservices-in-action](https://www.manning.com/books/microservices-in-action)

- More books: [https://www.developertoarchitect.com/books.html](https://www.developertoarchitect.com/books.html)

- The System Design Primer: [https://github.com/donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer)


## [Microservices Patterns](https://microservices.io/patterns/microservices.html)


- **Reliability Patterns**
  - Circuit Breaker Pattern
  
- **Service Discovery Patterns**
  - Client-side discovery
  - Server-side discovery
  - Service registry
  - Self registration
  - 3rd party registration

- **Cross-Cutting Concern Patterns**
  - External Configuration
  - Microservice Chassis

- **Observability Patterns**
  - Health Check API
  - Distributed Tracing
  - Performance Metrics
  - Log Aggregation: [Log consolidation vs log streaming (video)](https://www.developertoarchitect.com/lessons/lesson4.html), [Distributed Logging Architecture for Microservices
](https://dzone.com/articles/distributed-logging-architecture-for-microservices), [Distributed Logging Architecture in the Container Era](https://blog.treasuredata.com/blog/2016/08/03/distributed-logging-architecture-in-the-container-era/)
  - Audit logging
  - Distributed tracing
  - Exception tracking
  - Log deployments and changes
  
- **Data Management Patterns**
  - Saga Patterns
  - Event Sourcing
  - Database per Service
  - Shared Database
  - Command Query Responsibility Segregation (CQRS)
  - API Composition
  - Domain-Driven Design (DDD)

- **Integration Patterns**
  - Aggregator Pattern: [Orchestration Pattern (video)](https://www.developertoarchitect.com/lessons/lesson43.html), [Aggregation Pattern (video)](https://www.developertoarchitect.com/lessons/lesson44.html), [Microservices Integration Aggregators](https://dzone.com/articles/microservices-integration-aggregators), [Aggregator Pattern](https://akfpartners.com/growth-blog/microservice-aggregator-pattern)
  - Chained Microservice Design Pattern
  - Branch Pattern
  - Gateway Routing Pattern
  - Proxy Pattern
  - API Gateway Pattern
  - Backend For Front-End Pattern

- **Communication Style Patterns**
  - Remote Procedure Invocation
  - Messaging
  - Domain-specific protocol
  - Idempotent Consumer

- **Decomposition Patterns**
  - Sidecar Pattern
  - Bulkhead Pattern
  - Two-Phase Commit Protocol (2PC)
  - Decompose by Subdomain
  - Decompose by Business Capability
  - Self-contained Service
  - Service per team

- **Refactoring To Microservices**
  - Strangler Pattern
  - Anti-Corruption Layer

- **Transactional Messaging**
  - Transactional outbox
  - Transaction log tailing
  - Polling publisher

- **Deployment Patterns**
  - Multiple service instances per host
  - Service instance per host
  - Service instance per VM
  - Service instance per Container
  - Serverless deployment
  - Service deployment platform
  - Blue-Green Deployment Pattern

- **UI Patterns**
  - Client-Side UI Composition Pattern
  - Server-side page fragment composition

- **Security Patterns**
  - Access Token

- **Testing Patterns**
  - Consumer-driven contract test
  - Consumer-side contract test
  - Service component sest 

