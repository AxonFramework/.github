# Axon

The 'Axon Framework'-project consists of numerous repositories you can use in combination to build a flexible and sustainable application landscape.
Although the main repository, [Axon Framework](https://github.com/AxonFramework/AxonFramework), is undoubtedly the core, you can extend and optimize it by utilizing the other available tools.

#### Contents

* **[Axon Framework](#axon-framework)** 
* **[Getting Started](#getting-started)** 
* **[Receiving Help](#receiving-help)**
* **[Extensions](#extensions)** 
    * **[AMQP](#amqp)** - Extension adding [AMQP](https://en.wikipedia.org/wiki/Advanced_Message_Queuing_Protocol) support for event streaming
    * **[JGroups](#jgroups)** - Extension adding [JGroups](http://www.jgroups.org/) integration for command routing
    * **[JobRunr Pro](#jobrunr-pro)** - Extensions adding [JobRunr](https://www.jobrunr.io/en/) Pro integration for deadline management and event scheduling
    * **[Kafka](#kafka)** - Extension adding [Kafka](https://kafka.apache.org/) integration for event streaming
    * **[Kotlin](#kotlin)** - Extension enhancing the development experience when using [Kotlin](https://kotlinlang.org/)
    * **[MongoDB](#mongodb)** - Extension adding [MongoDB](https://www.mongodb.com/) integration for all Axon Framework components requiring storage
    * **[Multitenancy](#multitenancy)** - Extension adding building blocks to simplify [multitenancy](https://en.wikipedia.org/wiki/Multitenancy), particularly straightforward in combination with [Axon Server](https://developer.axoniq.io/axon-server/overview)
    * **[Reactor](#reactor)** - Extension providing Axon Framework-specific infrastructure components using the [Project Reactor](https://projectreactor.io/) API 
    * **[Spring Cloud](#spring-cloud)** - Extension adding [Spring Cloud](https://spring.io/projects/spring-cloud) integration for command routing
    * **[Spring Native](#spring-native)** - Experimental extension providing native compilation for Axon and Spring-based application through the [Spring Native](https://github.com/spring-attic/spring-native) project.  
    * **[Tracing](#tracing)** - Extension adding [Open Tracing](https://opentracing.io/) integration to Axon's infrastructure components
* **[Bill of Materials](#bill-of-materials)** 
* **[Inspector Axon](#inspector-axon)** - Specialized monitoring and management tooling for Axon Framework applications.
* **[IntelliJ IDEA Plugin](#intellij-idea-plugin)** - Plugin for IntelliJ IDEA simplifying Axon Framework development  
* **[AxonIQ Initializr](#axoniq-initializr)** - Webpage providing Axon Framework project scaffolding

For more information on anything Axon, please visit our websites, [https://developer.axoniq.io/](https://developer.axoniq.io/) and [https://axoniq.io](https://axoniq.io).
The former provides dedicated developer information, like explaining concepts, the available tooling, and blogs.
The latter contains information about AxonIQ, the company maintaining the 'Axon Framework'-project, providing information like the products, use cases, subscriptions, and training.

## Axon Framework

[Axon Framework](https://github.com/AxonFramework/AxonFramework) is a framework for building evolutionary, message-driven [microservice](https://developer.axoniq.io/microservices/overview) systems based on the principles of [Domain-Driven Design](https://developer.axoniq.io/domain-driven-design/overview) (DDD), [Command-Query Responsibility Separation](https://developer.axoniq.io/cqrs/overview) (CQRS), and [Event Sourcing](https://developer.axoniq.io/event-sourcing/overview).

Axon Framework provides you with the necessary building blocks to follow these principles.
The messaging support for commands, events, and queries is at the core of these building blocks.
The messaging basics enable an evolutionary approach towards microservices through the [location transparency](https://en.wikipedia.org/wiki/Location_transparency) they provide.

The building blocks include aggregate design handles, aggregate repositories, command buses, saga design handles, event stores, query buses, and more.
The framework provides sensible defaults for all of these components out of the box.

Axon Framework assists in distributing applications to support scalability or fault tolerance.
The most accessible and quick road forward would be to use [Axon Server](https://developer.axoniq.io/axon-server/overview) to seamlessly adjust message buses to distributed implementations.
It does so by being a dedicated message router and an efficient event store implementation for scalable event sourcing.

Next to Axon Server, several of [Axon's extensions](#extensions) can help in this space too.
However, they will require a little more handy work from the developer to set up, as knowledge of the tools supported by the extensions is required.

In conclusion, all this combined helps to create a well-structured application without worrying about the infrastructure.
Hence, your focus can shift from non-functional requirements to your business functionality.

## Documentation

## Samples

## Inspector Axon

## Extensions

Where [Axon Framework](#axon-framework) contains the core functionality for event-driven application construction, the extensions add valuable integrations with other tools and languages to enhance Axon's capabilities.
The extensions are intentionally split off from the main framework to not over encumber the user with unused functionality and obstruct the release cycles of the separate repositories.

The functionality of the extensions ranges from event streaming integrations with [AMQP](#amqp) and [Kafka](#kafka), database tooling like [Mongo](#mongodb), and language-specific integrations as with the [Kotlin](#kotlin) extension.
For more details about each extension, we refer to the subsections below.

### AMQP

### JGroups

### JobRunr Pro

### Kafka

### Kotlin

### MongoDB

### Multitenancy

### Reactor

### Spring Cloud

### Spring Native

### Tracing

## Bill of Materials

## Inspector Axon

## IntelliJ IDEA Plugin

## AxonIQ Initializr