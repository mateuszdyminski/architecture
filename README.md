# Architecture

Software Architecture - Principles and Practices Training Materials

## Agenda

* Part 1
  * Intro
  * Software Architecture - definition
  * Types of Software Architectures
    * Application architecture
    * System architecture
    * Solution architecture
    * Infrastructure architecture
  * Software architect
  * Architecture documentation and visualization
    * C4
  * Archtecture Metrics
  * Company Culure in Context of Software Architecture
  * Key Software Development Concepts
    * YAGNI
    * SOLID
    * DRY
    * KISS
  * Domain Driven Design
  * Event Storming – Big Picture
  * Tips and Trics
* Part 2
  * System Architecture Patterns
    * Distributed applications
    * Monolith applications
    * Monolith with modules
  * Application Architectures:
    * Layered architecture
    * Pipes and Filters architecture
    * Modularity architecture
    * Hexagonal/Clean/Onion/Ports and Adapters architecture
    * Microkernel architecture
    * Event-Driven architecture
      * Event Sourcing
      * CQRS
    * Serverless architecture
  * Modern Architectural Concepts - independent from the architecture type
    * 12 Factor application
    * Cloud native apps
    * Containers
    * Kubernetes
    * Service Mesh
    * Change Data Capture
  * Communication
    * Asynchronus vs synchronous
    * Synchronous
      * REST
      * GraphQL
      * RPC
      * API Gateway
      * Backend for frontend
    * Asynchronous
      * Messaging
      * Messaging with order
  * Testing microservices
    * Consumer-driven contract
    * Fitness function
* Part 3
  * DevOps culture
  * CI/CD
  * GitOps
  * GitSecOps
  * Deployment models
    * Continuous Deployment and Delivery
    * Zero-downtime deployments
    * Graceful shutdowns
    * Canary deployment
    * A/B testing
  * Operations
    * Services Health
    * Log aggregators
    * Metrics/insrtumentation
    * Distributed tracing
    * Alarms
  * Chaos engineering
  * Security
    * Security culture
      * Production cluster access
      * Responsibilities
    * Security patterns and tools
      * IAM solutions
      * Secrets/passwords management
      * Code scanning
      * Containers scaning

## External Materials & Credits

This presentation woudn't be possible without following resources:

### Articles

* [Who needs Architect](https://martinfowler.com/ieeeSoftware/whoNeedsArchitect.pdf)
* [Applying Conway's Law to improve your software development](https://www.thoughtworks.com/insights/blog/applying-conways-law-improve-your-software-development)
* [Conways Law](https://radekmaziarka.pl/2019/02/25/conways-law-jak-struktura-organizacji-wplywa-na-osiagane-rezultaty/)

* [DDD basics](https://bottega.com.pl/pdf/materialy/sdj-ddd.pdf)
* [DevOps Culture](https://martinfowler.com/bliki/DevOpsCulture.html)
* [Guide To GitOps](https://www.weave.works/technologies/gitops/)
* [GitSecOps](https://about.gitlab.com/solutions/dev-sec-ops/)
* [Chaos Engineering](https://principlesofchaos.org/)
* [The RED Method: key metrics for microservices architecture](https://www.weave.works/blog/the-red-method-key-metrics-for-microservices-architecture/)
* [MonolithFirst rule](https://martinfowler.com/bliki/MonolithFirst.html)
* [Modular monolith architectural drivers](https://www.kamilgrzybek.com/design/modular-monolith-architectural-drivers)
* [Modular monolith primer](http://www.kamilgrzybek.com/design/modular-monolith-primer/)
* [Pipes and Filter Architecture](https://docs.microsoft.com/en-us/azure/architecture/patterns/pipes-and-filters)
* [Example of Hexagonal architecture](https://blog.octo.com/en/hexagonal-architecture-three-principles-and-an-implementation-example/)
* [CQRS pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
* [Serverless concept](https://martinfowler.com/articles/serverless.html)
* [12 Factor Application](https://12factor.net/)
* [Service Mesh basics](https://codilime.com/blog/is-network-service-mesh-a-service-mesh)
* [Syncs vs Async](https://dzone.com/articles/patterns-for-microservices-sync-vs-async)
* [GraphQL intro](http://slidedeck.io/OlegIlyenko/presentation-graphql-introduction)
* [Backend for Frontend basics](https://samnewman.io/patterns/architectural/bff/)
* [Backend For Frontend example](https://www.thoughtworks.com/insights/blog/bff-soundcloud)
* [Consumer Driven Contract](https://reflectoring.io/consumer-driven-contracts-with-angular-and-pact)
* [Fitness function driven design](https://www.thoughtworks.com/insights/blog/fitness-function-driven-development)

### To watch

* [Visualising software architecture with the C4 model - Simon Brown](https://www.youtube.com/watch?v=x2-rSnhpw0g)
* [Common mistakes when moving to microservices & cloud](https://www.youtube.com/watch?v=jo46-CP6ywU)
* [Robert C. Martin (Uncle Bob), Clean Architecture and Design](https://www.youtube.com/watch?v=2dKZ-dWaCiU)
* [Streaming Database Changes with Debezium](https://www.youtube.com/watch?v=IOZ2Um6e430)

### Books

* Design Patterns: Elements of Reusable Object-Oriented Software [1994] by Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides (Gang of Four a.k.a. GoF)
* Clean Code: A Handbook of Agile Software Craftsmanship [2007] by Robert C. Martin (“Uncle Bob”)
* Clean Architecture: A Craftsman’s Guide to Software Structure and Design [2016] by Robert C. Martin (“Uncle Bob”)
* Refactoring: Improving the Design of Existing Code (2nd Edition) [2018] by Martin Fowler
* The Pragmatic Programmer (2nd Edition): Your Journey to Mastery, 20th Anniversary Edition [2019] by Andrew Hunt, David Thomas
* Domain-Driven Design: Tackling Complexity in the Heart of Software [2003] by Eric Evans
* Building Microservices: Designing Fine-Grained Systems [2015] by Sam Newman
* Designing Data-Intensive Applications [2015] by Martin Kleppmann
* SRE | Site Reliability Engineering: How Google Runs Production Systems [2016] by Betsy Beyer, Niall Richard Murphy, Chris Jones, Jennifer Petoff
* The Phoenix Project (A Novel About IT, DevOps, and Helping Your Business Win) [2018] by Gene Kim, Kevin Behr, George Spafford
* Designing Event-Driven Systems [2018] by Ben Stopford
