# Software Architecture - Principles and Practices

Agenda of 3-days training *Software Architecture - Principles and Practices*.

## Day 1

* Intro
  * Software Architecture definition
    * Software Architecture Levels:
      * Application level
      * Solution level  
      * Enterprise level
      * Infrastracture level
  * Software Architect
    * Role
    * Types - same as levels
      * Application architect
      * Solution architect
      * Enterprise architect
      * Infrastracture architect
* Architecture documentation and visualization
  * C4
  * UML
  * BPMN
* Domain Driven Design
  * Domains and subdomains
  * Bounded context
* Event Storming – Big Picture
* Archtecture Metrics
* Company Culure in Context of Software Architecture
* Architecture Guild
  * How to design it to help making Architecture decisions
* Key Software Development Concepts
  * YAGNI
  * SOLID
  * DRY
  * KISS
* Tips and Trics
  * Whiteboard iteration vs Sprint iteration
  * Pencil and paper vs VS Code
  * How to make architecture decisions
  * RFC

## Day 2

* Application Architectures:
  * Layered architecture
  * Pipes and Filters architecture
  * Modularity architecture
  * Hexagonal/Clean/Onion/Ports and Adapters architecture
  * Microkernel architecture
  * Event-Driven architecture
  * Serverless architecture

* System Architecture Patterns
  * Distributed applications
  * Monolith applications
  * Monolith with modules

* Architecture concepts - independent from the application arch
  * 12 Factor application
  * Cloud native apps
  * Containers
  * Service Mesh

* Communication
  * Asynchronus vs synchronous
  * Synchronous
    * REST vs GraphQL vs RPC
    * REST
      * HATEOAS
      * How to design beautiful APIs
      * When to use it
    * GraphQL
      * Pros/cons
      * When to use it
    * RPC
      * Pros/Cons
      * When to use it
      * RPC is not always CORBA - gRPC
    * Backend for frontend
  * Asynchronous
    * Messaging
    * Messaging with order
  * Public APIs
    * API Gateway
  * Service discovery
* Testing microservices
  * Consumer-driven contract
  * Consumer-side contract
  * Service component
  * Smoke tests
* Event Sourcing
* CQRS

## Day 3

* Continuous Integration
  * How to design perfect CI pipelines
* DevOps culture
* GitOps
* GitSecOps
* Infrastructure
  * Public vs private cloud
  * Cloud
    * Cloud capabilities
    * SaaS vs PaaS
    * Vendor lock-in problems
  * Deployment models
    * Where? On-prem vs public cloud vs public VMs
      * Continuous Deployment and Delivery
        * Zero-downtime deployments
        * Graceful shutdowns
        * Canary deployment
        * A/B testing
  * Chaos engineering

* Operations
  * Observability
  * Services Health
  * Log aggregators
  * Metrics/insrtumentation
  * Audit logging
  * Distributed tracing
  * Alarms

* Security
  * Security culture
    * Production cluster access
    * Responsibilities
  * Security patterns and tools
    * IAM solutions
    * Secrets/passwords management
    * Security between services
    * Audit logs
    * Static security analysis
      * VMs scanning
      * Containers scaning
      * Code scanning

* Refactoring of Legacy Systems
  * Patterns

### Sources

* Github roadmaps:
  * [https://github.com/AlaaAttya/software-architect-roadmap](https://github.com/AlaaAttya/software-architect-roadmap)
  * [https://github.com/justinamiller/SoftwareArchitect](https://github.com/justinamiller/SoftwareArchitect)
* [DNA](DNA-mapa-A1.pdf)
* [Pawel presentations](202109_NobleProg_EY_SoftwareArchitecture.pdf)
* [Books](https://medium.com/@ThilinaAshenGamage/the-best-software-architecture-books-of-all-time-b82b63bb853b)
* tbd

### To read

* [https://www.infoq.com/articles/architecture-guild-800-friends/](https://www.infoq.com/articles/architecture-guild-800-friends/)
* tbd

### To watch

* [https://www.youtube.com/watch?v=x2-rSnhpw0g](https://www.youtube.com/watch?v=x2-rSnhpw0g)
* [https://www.youtube.com/watch?v=yhYFL4ujYqY](https://www.youtube.com/watch?v=yhYFL4ujYqY)
* [https://www.youtube.com/watch?v=jo46-CP6ywU](https://www.youtube.com/watch?v=jo46-CP6ywU)
* tbd
