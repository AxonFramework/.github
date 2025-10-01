<p align="center">
    <img src="../images/AxonIQLogo-2025.png" alt="Axoniq logo" width="600" height="200">
</p>

<h1 align="center"></h1>

<p align="center">
  Build modern event-driven systems with Axoniq technology
  <br>
  <a href="https://www.axoniq.io/"><strong>Learn more at our website »</strong></a>
  <br>
  <br>
  <a href="https://www.axoniq.io/products/axon-framework">Axon Framework</a>
  ·
  <a href="https://www.axoniq.io/products/axon-server">Axon Server</a>
  ·
  <a href="https://www.axoniq.io/products/axoniq-console">AxonIQ Console</a>

</p>

#

<p><br/></p>
<img src="../images/AxonFrameworkLogo-2025.png" alt="Axon Framework logo" width="500">

The Axon Framework is an open source framework that's 100% Java and enables developers to build scalable and maintainable applications using a message-driven approach. It simplifies the complexities of developing distributed systems by providing a structured way to handle commands, events, and queries within your application. [If you're not familiar with the Event Sourcing pattern](https://www.axoniq.io/concepts/cqrs-and-event-sourcing), you can learn more about it on our website.

At its core, the Axon Framework encourages an architecture where components communicate through messages, which promotes loose coupling and increases flexibility. This messaging system allows different parts of your application to interact without needing to know the internal workings of each other, making your system more modular and easier to manage. If you already use tools and technologies that enable your applications to utilize a pub/sub pattern, then you already understand the basics of message driven and event driven architectures.

The Axon Framework further enhances your applications and services by enabling you to support Event Sourcing, a powerful architectural pattern where state changes are recorded as a sequence of events. Why is this important? Well, instead of just storing the current state in a traditional database, every change is logged, providing a complete history of how the data arrived at its current form. This can be incredibly useful for auditing, debugging, and even recreating past states of your application when necessary.

For JVM-based developers working with microservices, the Axon Framework offers tools to manage the complexities inherent in distributed systems. By leveraging its messaging and event-handling capabilities, you can build applications that are not only scalable and robust but also easier to extend and maintain over time.

## How Can I Get Started with the Axon Framework?

We highly recommend all developers to get started by going to the [Axoniq Documentation Portal](https://docs.axoniq.io/home/), which provides links to our tutorials, guides, and reference documentation.

Furthermore, below are several other helpful resources:
* 👨‍💻 [Go to the Axon Framework Github repo](https://github.com/AxonFramework/AxonFramework) to view the source code and follow the project 
* 📖 [Read the tutorial](https://docs.axoniq.io/bikerental-demo/main/) on building a Bike Rental application from scratch
* 📺 [Watch our in-depth video training courses](https://academy.axoniq.io/) in the Axoniq Academy
* 🙋 [Ask questions](https://discuss.axoniq.io/) in our help forum, Discuss.
* ⬇️ [See additional code samples](https://github.com/AxonIQ/code-samples) in our code samples repository


<p><br/></p>
<p><br/></p>
<img src="../images/AxonServerLogo-2025.png" alt="Axon Server logo" width="500">

For developers who are serious about Event Sourcing, we offer the Axon Server. The Axon Server is designed to simplify the development of event-driven applications by acting as both an Event Store and a message router. Therefore, it is as a central hub for managing and distributing events, commands, and queries within your application ecosystem. By handling these critical aspects, Axon Server allows developers to focus more on business logic rather than the complexities of communication and data storage in distributed systems.

When developing microservices, coordinating interactions between multiple services can become quite challenging. This is especially the case as the system scales to handle more users or additional features requested by customers and stakeholders. Axon Server addresses this by providing seamless and scalable message routing between services. It ensures that messages reach their intended targets and that events are efficiently broadcasted to all interested parties. 

In addition to functioning as a message router, Axon Server enables apps and microservices to be Event Sourced. This means that all changes in the application state are stored as a sequence of events. This allows the application to reconstruct its state at any point in time by replaying these events. For developers unfamiliar with event sourcing, this means you have a complete history of what happened in your system, which is invaluable for debugging, auditing, and understanding complex behaviors. This is a revolutionary approach to traditional application development, however the architectural pattern is proven to create better and more resilient software systems.

By incorporating Axon Server into your applications, especially those built with microservices, you gain a robust platform for managing the flow of data and commands across your system. It abstracts the complexities of message handling and event storage, enabling you to build scalable, maintainable, and high-performing applications. This allows you to deliver features faster and adapt more readily to changing business requirements.

## How Can I Get Started with Axon Server?

If you're getting started with the Axon Server, then we recommend that you go to the [Axoniq Documentation Portal](https://docs.axoniq.io/home/), which provides links to our tutorials, guides, and reference documentation.

Furthermore, below are several other helpful resources:
* ⬇️ [Download the latest release](https://www.axoniq.io/download) of Axon Server. It's free and easy to install and customize
* 📖 [Read the lateast release notes](https://docs.axoniq.io/axon-server-reference/v2024.1/release-notes/) to see the latest features 
* 📖 [Read the tutorial](https://docs.axoniq.io/bikerental-demo/main/) on building a Bike Rental application from scratch
* 📺 [Watch our in-depth video training courses](https://academy.axoniq.io/) in the Axoniq Academy
* 🙋 [Ask questions](https://discuss.axoniq.io/) in our help forum, Discuss




<h1 align="center"></h1>

## Extensions

Where [Axon Framework](#axon-framework) contains the core functionality for event-driven application construction, the extensions add valuable integrations with other tools and languages to enhance Axon's capabilities.
The extensions are intentionally split off from the main framework to not over encumber the user with unused functionality and obstruct the release cycles of the separate repositories.

The functionality of the extensions ranges from event streaming integrations with [AMQP](#amqp) and [Kafka](#kafka), database tooling like [Mongo](#mongodb), and language-specific integrations as with the [Kotlin](#kotlin) extension.
For more details about each extension, we refer to the subsections below.

#### Contents

 * **[AMQP](#amqp)** - Extension adding [AMQP](https://en.wikipedia.org/wiki/Advanced_Message_Queuing_Protocol) support for event streaming
 * **[JGroups](#jgroups)** - Extension adding [JGroups](http://www.jgroups.org/) integration for command routing
 * **[JobRunr Pro](#jobrunr-pro)** - Extensions adding [JobRunr](https://www.jobrunr.io/en/) Pro integration for deadline management
 * **[Kafka](#kafka)** - Extension adding [Kafka](https://kafka.apache.org/) integration for event streaming
 * **[Kotlin](#kotlin)** - Extension enhancing the development experience when using [Kotlin](https://kotlinlang.org/)
 * **[MongoDB](#mongodb)** - Extension adding [MongoDB](https://www.mongodb.com/) integration for all Axon Framework components requiring storage
 * **[Multitenancy](#multitenancy)** - Extension adding building blocks to simplify [multitenancy](https://en.wikipedia.org/wiki/Multitenancy), particularly straightforward in combination with [Axon Server](#axon-server)
 * **[Reactor](#reactor)** - Extension providing Axon Framework-specific infrastructure components using the [Project Reactor](https://projectreactor.io/) API 
 * **[Spring AoT](#spring-aot)** - Extension providing Ahead of Time compilation for Axon and Spring-based application through Spring Boot's [ahead of time](https://docs.spring.io/spring-boot/reference/packaging/aot.html) processing
 * **[Spring Cloud](#spring-cloud)** - Extension adding [Spring Cloud](https://spring.io/projects/spring-cloud) integration for command routing
 * **[Tracing](#tracing)** - Extension adding [Open Tracing](https://opentracing.io/) integration to Axon's infrastructure components, superseded by integrated [Open Telemetry](https://opentelemetry.io/) support

### AMQP

The [AMQP Extension](https://github.com/AxonFramework/extension-amqp) repository provides support for the [Advanced Message Queuing Protocol](https://en.wikipedia.org/wiki/Advanced_Message_Queuing_Protocol) (AMQP).

Users can add this extension to, for example, include a [RabbitMQ](https://www.rabbitmq.com/) integration with their Axon Framework application.
Setting up this integration allows you to publish Axon events to an AMQP exchange. 
Events can also be read from exchanges and handled by event processors, providing means of integrating with other services.

In doing so, you would enable (micro)service communication through event streaming.
Or, you can attach a (third-party) application with your Axon Framework application, communicating through AMQP.

You should regard this extension as a partial replacement of [Axon Server](#axon-server) as, compared to Axon Server, it only covers event streaming.

Please read the [AMQP section](https://docs.axoniq.io/amqp-extension-reference/latest/) of the documentation for more information about this extension.

### JGroups

The [JGroups Extension](https://github.com/AxonFramework/extension-jgroups) repository enables integration with [JGroups](http://www.jgroups.org/).

You can use this extension to enable command routing in a distributed environment.
As command routing differs from, for example, load balancing REST operation, it is highly recommended to use a distributed command routing solution whenever you have several applications and/or application instances that need to communicate with one another.

The extension achieves this by implementing the `CommandRouter` and `CommandBusConnector`, consolidated in the `JGroupsConnector`.
This connector provides the service discovery and message routing required to pass `CommandMessages` from one application (instance) to another.

You should regard this extension as a partial replacement of [Axon Server](#axon-server) as, compared to Axon Server, it only covers command routing.

Please read the [JGroups section](https://docs.axoniq.io/jgroups-extension-reference/latest/) of the documentation for more information about this extension.

### JobRunr Pro

The [JobRunr Pro Extension](https://github.com/AxonFramework/extension-jobrunrpro) repository provides support for the "pro" edition of [JobRunr](https://www.jobrunr.io/en/).

Users can benefit from this extension whenever they have:

1. Acquired [JobRunr Pro](https://www.jobrunr.io/en/pricing/), and
2. want to use Axon's [deadline management](https://docs.axoniq.io/axon-framework-reference/latest/deadlines/deadline-managers/) functionality.

We constructed this extension as some feature on the `DeadlineManager` API cannot be supported with the free edition of JobRunr.

Please read the [Jobrunr Pro section](https://docs.axoniq.io/jobrunr-pro-extension-reference/latest/) of the documentation for more information about this extension.

### Kafka

The [Kafka Extension](https://github.com/AxonFramework/extension-kafka) repository enables integration with [Kafka](https://kafka.apache.org/).

Setting up a Kafka integration with your Axon Framework applications allows you to:
1. Publish Axon Event Messages onto one or more Kafka topics, and
2. to read Kafka Consumer Records converted to Axon Event Messages into your `@EventHandler` annotated methods.

In doing so, you would enable (micro)service communication through event streaming.
Or, you can attach a (third-party) application with your Axon Framework application, communicating through Kafka.

Note that the Axon Framework team **does not** intend to support [Event Sourcing](https://www.axoniq.io/concepts/cqrs-and-event-sourcing) through the Kafka Extension.
Although there are Kafka-focused articles explaining how to achieve this, we find this a suboptimal solution leading to predicaments in the future.
We thus suggest you choose [Axon Server](#axon-server), an RDBMS solution or the [MongoDB Extension](#mongodb) to store your events and subsequently support event sourcing.

You should regard this extension as a partial replacement of Axon Server as, compared to Axon Server, it only covers event streaming.

Please read the [Kafka section](https://docs.axoniq.io/kafka-extension-reference/latest/) of the documentation for more information about this extension.

### Kotlin

The [Kotlin Extension](https://github.com/AxonFramework/extension-kotlin) repository eases Axon Framework development for [Kotlin](https://kotlinlang.org/)-based applications.

You can use this extension to relieve some of the "awkwardness" of the Axon Framework API when using Kotlin to build your application(s).
It does so by providing reified methods of several of Axon's infrastructure components, like the [command](https://docs.axoniq.io/kotlin-extension-reference/latest/commands/#commandgateway) and [query gateway](https://docs.axoniq.io/kotlin-extension-reference/latest/queries/#querygateway), [upcasters](https://docs.axoniq.io/kotlin-extension-reference/latest/events/#_event_upcasters), and the [test fixtures](https://docs.axoniq.io/axon-framework-reference/latest/testing/).

Please read the [Kotlin section](https://docs.axoniq.io/kotlin-extension-reference/latest/) of the documentation for more information about this extension.

### MongoDB

The [MongoDB Extension](https://github.com/AxonFramework/extension-mongo) repository enables [MongoDB](https://www.mongodb.com/) as a storage solution throughout the framework.

Users can set this extension whenever they want to use MongoDB to store:
- [Events](https://docs.axoniq.io/axon-framework-reference/latest/events/event-bus-and-event-store/)
- [Sagas](https://docs.axoniq.io/axon-framework-reference/latest/sagas/)
- [Tracking Tokens](https://docs.axoniq.io/axon-framework-reference/latest/events/event-processors/streaming/#tracking-tokens)
- [Dead Letters](https://docs.axoniq.io/axon-framework-reference/latest/events/event-processors/#dead-letter-queue)

Especially when you store Query Models or inside a MongoDB collection, we recommend you keep the tracking tokens of the [streaming processor](https://docs.axoniq.io/axon-framework-reference/latest/events/event-processors/streaming/) inside MongoDB as well.
By doing so, you ascertain that the framework uses a single transaction to update the model and token.

The same logic applies to Sagas that are backed by streaming processors and stored in MongoDB; storing the tokens next to the saga instances makes the application more robust.

Note that although you can use this extension to adjust MongoDB into an event store, we do not necessarily recommend this.
During the lifecycle of this extension, we have noticed predicaments with how MongoDB behaves, causing the event store to act suboptimal from a performance perspective.
We thus recommend either [Axon Server](#axon-server) (the highest level of performance for event storage) or an RDBMS of choice instead.

You should regard this extension as a partial replacement of Axon Server as, compared to Axon Server, it only covers event storage.

Please read the [MongoDB section](https://docs.axoniq.io/mongodb-extension-reference/latest/) of the documentation for more information about this extension.

### Multitenancy

The [Multitenancy Extension](https://github.com/AxonFramework/extension-multitenancy) repository provides integrated support for [multitenancy](https://en.wikipedia.org/wiki/Multitenancy) to your Axon Framework application.

By adding this extension to your [Axon Framework](#axon-framework) application(s), you receive multi-tenant versions of all the infrastructure components the framework provides.
In doing so, you can run a single instance of an application but serve many of your tenants in one go.
Interfaces like the `CommandBus`, `EventProcessor`, and `SequencedDeadLetterQueue` are implemented by this extension to delegate tenant-specific tasks to concrete implementations of these components.

If you combine Axon Framework and the Multitenancy Extension with [Axon Server](#axon-server), the multitenancy experience of your app(s) is seamless.
The extension achieves this by utilizing Axon Server's [multi-context](https://docs.axoniq.io/axon-server-reference/latest/axon-server/administration/multi-context/) behavior to dynamically create new tenants (read: a context per tenant) whenever you register them.
It is usable without Axon Server, but you will be inclined to implement factories for the infrastructure components yourself.

Please read the [Multitenancy section](https://docs.axoniq.io/multitenancy-extension-reference/latest/) of the documentation for more information about this extension.

### Reactor

The [Reactor Extension](https://github.com/AxonFramework/extension-reactor) repository provides [Axon Framework](#axon-framework) infrastructure components using the [Project Reactor](https://projectreactor.io/) API.

You can add this extension to your Axon Framework project to use results like `Mono` and `Flux` on framework components.
It provides Reactor versions of Axon's gateways, allowing you to leverage the reactive API on the edge of your Axon Framework application.

Please read the [Reactor section](https://docs.axoniq.io/reactor-extension-reference/latest/) of the documentation for more information about this extension.

### Spring AoT

The [Spring AoT Extension](https://github.com/AxonFramework/extension-spring-native) repository enables integration with the Spring Boot's [ahead of time](https://docs.spring.io/spring-boot/reference/packaging/aot.html) processing.

This extension allows you to compile to a native image whenever you combine Axon Framework with Spring Boot.

Please read the [Spring AoT section](https://docs.axoniq.io/spring-aot-extension-reference/latest/) of the documentation for more information about this extension.

### Spring Cloud

The [Spring Cloud Extension](https://github.com/AxonFramework/extension-springcloud) repository enables integration with [Spring Cloud](https://spring.io/projects/spring-cloud).

You can use this extension to enable command routing in a distributed environment.
As command routing differs from, for example, load balancing REST operation, it is highly recommended to use a distributed command routing solution whenever you have several applications and/or application instances that need to communicate with one another.

The extension achieves this by implementing the `CommandRouter` and `CommandBusConnector`, consolidated in the `SpringCloudeCommandRouter` and `SpringHttpCommandBusConnector`, respectively.
This connector provides the service discovery and message routing required to pass `CommandMessages` from one application (instance) to another.

Since the implementation uses the Spring Cloud discovery interfaces to perform the service discovery, you are able to choose a multitude of implementations to enable distributed command routing.
You can, for example, use implementation like [Netflix](https://spring.io/projects/spring-cloud-netflix), [Consul](https://spring.io/projects/spring-cloud-consul), [Zookeeper](https://spring.io/projects/spring-cloud-zookeeper), [Kubernetes](https://spring.io/projects/spring-cloud-kubernetes), and many more.

You should regard this extension as a partial replacement of [Axon Server](#axon-server) as, compared to Axon Server, it only covers command routing.

Please read the [Spring Cloud section](https://docs.axoniq.io/spring-cloud-extension-reference/latest/) of the documentation for more information about this extension.

### Tracing

The [Tracing Extension](https://github.com/AxonFramework/extension-tracing) repository enables integration with [Open Tracing](https://opentracing.io/).

When using this extension, you will replace the `Command-` and `QueryGateway` with implementations that attach span information to your `Messages`.
Furthermore, when handling a `Message`, a dedicated `MessageHandlerInterceptor` ensures the span is populated on the overall trace.

Although this is valuable, it is essential to mention that the Open Tracing implementation has been archived in favor of [Open Telemetry](https://opentelemetry.io/).
Furthermore, as of [Axon Framework](#axon-framework) version [4.6.0](https://docs.axoniq.io/axon-framework-reference/latest/release-notes/major-releases/#_release_4_6), the framework provides native support for [Open Telemetry](https://opentelemetry.io/).

We thus recommend that you use the [integrated tracing support](https://docs.axoniq.io/axon-framework-reference/latest/monitoring/tracing/) whenever you are on Axon Framework version 4.6 or above.

Nonetheless, we still maintain and update the Tracing Extension for the time being.
As such, you can be certain the extension still works as intended.

Please read the [Tracing section](https://docs.axoniq.io/tracing-extension-reference/latest/) of the documentation for more information about this extension.


<br>
<p></p>
</br>


# Bill of Materials

The [Bill of Materials](https://github.com/AxonFramework/axon-bom) repository of Axon Framework is a dedicated dependency providing compatible versions of the [framework](#axon-framework) and [extensions](#extensions).
Hence, by adding `axon-bom` to your dependency management system, you ensure the compatibility of Axon's dependencies.
As such, we recommend you use this dependency whenever you combine Axon Framework with any of the extensions.

## IntelliJ IDEA Plugin

The [Axon Framework IntelliJ Plugin](https://plugins.jetbrains.com/plugin/18628-axon-framework) is a plugin you can add when using [IntelliJ IDEA](https://www.jetbrains.com/idea/).
Including this plugin eases your developer experience of [Axon Framework](#axon-framework) 4.x-based applications.

Some of the features this plugin adds to IntelliJ are:
* Line markers to visualize messages
* Axon Framework-specific code structure inspections
* Easy access to the documentation

Please read the [README](https://github.com/AxonFramework/IdeaPlugin#readme) of the IdeaPlugin project to learn more about this plugin.

## Data Protection Module

As you may know, [Event Sourcing](https://www.axoniq.io/concepts/cqrs-and-event-sourcing) dictates that you never remove or update events.
With the introduction of Data Protection Laws like [GDPR](https://gdpr-info.eu/), developers using Event Sourcing in their applications are thus faced with a predicament.
A predicament you are required to resolve by law.

As one of [Axon Framework's](#axon-framework) pillars is to enable Event Sourcing, we are inclined to provide a solution.
As such, AxonIQ constructed the [Data Protection Module](https://www.axoniq.io/blog/protect-sensitive-data-in-an-event-sourced-application) in response to these new requirements.

The Data Protection Module is a Java library providing the tooling to mark specific data inside events as ["personally identifiable information"](https://en.wikipedia.org/wiki/Personal_data) (PII for short).
Then when you store the event or send it over a network, you can encrypt the PII within the event to protect it.
From there, you can choose a preferred key management system, with options like relation databases, hardware security modules, and [HashiCorp Vault](https://www.hashicorp.com/products/vault).

In combination with Axon Framework, you can implement the described behavior seamlessly by using dedicated annotations and a custom [`Serializer`](https://docs.axoniq.io/axon-framework-reference/latest/serialization/) as provided by the Data Protection Module.
If you require more information about the Data Protection Module, be sure to [reach out](https://www.axoniq.io/contact).  
