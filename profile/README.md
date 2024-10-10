# Axon

[Axon Framework](#axon-framework) is a framework for building evolutionary, [message-driven microservice](https://www.axoniq.io/concepts/event-driven-microservices) systems based on the principles of [Domain-Driven Design](https://www.axoniq.io/concepts/domain-driven-design) (DDD), [Command-Query Responsibility Separation](https://www.axoniq.io/concepts/cqrs-and-event-sourcing) (CQRS), and [Event Sourcing](https://www.axoniq.io/concepts/cqrs-and-event-sourcing).

The whole 'Axon Framework'-project consists of numerous repositories you can use in combination with one another to build a flexible and sustainable application landscape.
Although the main repository, [Axon Framework](https://github.com/AxonFramework/AxonFramework), is undoubtedly the core, you can optimize and enhance it by utilizing the other available tools.

#### Contents

* **[Axon Framework](#axon-framework)** 
* **[Getting Started](#getting-started)** 
* **[Receiving Help](#receiving-help)**
* **[Axon Server](#axon-server)** - Purpose-built Event Store and Messaging Platform for commands and queries 
* **[Extensions](#extensions)**
* **[AxonIQ Console](#axoniq-console)** - Specialized monitoring and management tooling for Axon Framework applications.
* **[Bill of Materials](#bill-of-materials)** 
* **[IntelliJ IDEA Plugin](#intellij-idea-plugin)** - Plugin for IntelliJ IDEA simplifying Axon Framework development
* **[Data Protection Module](#data-protection-module)** - Separate tool from AxonIQ simplifying implementation of Data Protection Laws like [GDPR](https://gdpr-info.eu/)

For more information on anything Axon, please visit our website, [https://axoniq.io](https://axoniq.io), or our documentation, [https://docs.axoniq.io](https://docs.axoniq.io).
It contains information about AxonIQ, the company maintaining the 'Axon Framework'-project, providing information like the products, use cases, subscriptions, and training.

## Axon Framework

[Axon Framework](https://github.com/AxonFramework/AxonFramework) provides you with the necessary building blocks to follow these principles.
The messaging support for commands, events, and queries is at the core of these building blocks.
The messaging basics enable an evolutionary approach towards microservices through the [location transparency](https://en.wikipedia.org/wiki/Location_transparency) they provide.

The building blocks include aggregate design handles, aggregate repositories, command buses, saga design handles, event stores, query buses, and more.
The framework provides sensible defaults for all of these components out of the box.

Axon Framework assists in distributing applications to support scalability or fault tolerance.
The most accessible and quick road forward would be to use [Axon Server](#axon-server) to seamlessly adjust message buses to distributed implementations.
It does so by being a dedicated message router and an efficient event store implementation for scalable event sourcing.

Next to Axon Server, several of [Axon's extensions](#extensions) can help in this space too.
However, they will require a little more handy work from the developer to set up, as knowledge of the tools supported by the extensions is required.

In conclusion, all this combined helps to create a well-structured application without worrying about the infrastructure.
Hence, your focus can shift from non-functional requirements to your business functionality.

If you want to learn more about Axon Framework, you can visit the product page [here](https://www.axoniq.io/products/axon-framework).

## Getting started

Numerous resources can help you on your journey in using Axon Framework.
A good starting point is the [AxonIQ Docs](https://docs.axoniq.io/home/), which contains resources like basics, guides, and reference documentation.

There are, however, a lot more resources you can benefit from.

For example, training:
* We have our very own [Academy](https://academy.axoniq.io/)!
  The introductory courses are free, followed by more in-depth (paid) courses.
* Next to the Academy, there are dedicated training sessions provided by AxonIQ.
  Check out the [Training courses](https://www.axoniq.io/training) page for more information about these.

Or, the references and forum:
* The [documentation](https://docs.axoniq.io/) explains all components maintained within Axon Framework's products.
* If the guide doesn't help, our [forum](https://discuss.axoniq.io/) provides a place to ask your questions during development.
* Posting questions on [StackOverflow](https://stackoverflow.com/) next to Axon's forum is also possible. When doing so, add the `axon` tag! This tag will nudge AxonIQ developers, which will cover those on a best-effort basis.

And several sample projects you can check out:
* The [Bike Rental Demo](https://docs.axoniq.io/bikerental-demo/main/) guide will help you to start a basic Axon Framework application from scratch.
* The [Giftcard Demo](https://github.com/AxonIQ/giftcard-demo) contains a simple gift card management
* The [Hotel Demo](https://github.com/AxonIQ/hotel-demo) shows a fleshed-out example of using Axon Framework.
* The [Code Samples](https://github.com/AxonIQ/code-samples) repository contains in-depth samples for special use cases.
  It, for example, contains subjects like [distributed exception handling](https://github.com/AxonIQ/code-samples/tree/master/distributed-exceptions), [sagas](https://github.com/AxonIQ/code-samples/tree/master/saga), [upcasters](https://github.com/AxonIQ/code-samples/tree/master/upcaster), [multitenancy](https://github.com/AxonIQ/code-samples/tree/main/multitenancy), [set-based validation](https://github.com/AxonIQ/code-samples/tree/master/set-based-validation-actor-model), and many more.

## Receiving help

Do you need help with using any of our libraries or products?
Know that we want to help you out the best we can!
There are a couple of things to consider when you're traversing anything Axon:

* Checking the [documentation page](https://docs.axoniq.io) should be your first stop when anything is unclear.
* When the documentation does not cover your predicament, we would greatly appreciate it if you could file an [issue](https://github.com/AxonFramework/AxonFramework/issues/new/choose) for it.
  Drafting issues helps us to improve the documentation for all users based on your valuable input.
* Our [forum](https://discuss.axoniq.io/) provides a space to communicate with the Axon community to help you out.
  AxonIQ developers will help you out on a best-effort basis.
  And if you know how to help someone else, we greatly appreciate your contributions!
* We also monitor Stack Overflow for any question tagged with [**axon**](https://stackoverflow.com/questions/tagged/axon).
  Similarly to the forum, AxonIQ developers help out on a best-effort basis.
* We built [AxonIQ Console](#axoniq-console) purposefully to help you inspect your Axon Framework application and Axon Server instances in detail.
  Attaching it to your project is straightforward, providing you with a dashboard with specialized metrics and message flow diagrams, to name a few.
* If you are developing in [IntelliJ IDEA](https://www.jetbrains.com/idea/), know that we have constructed a [plugin](#intellij-idea-plugin) to streamline the development of Axon-based applications.

## Axon Server

Through [Axon Framework](#axon-framework), users can quickly build flexible applications by leveraging the building blocks for [DDD](https://www.axoniq.io/concepts/domain-driven-design), [CQRS](https://www.axoniq.io/concepts/cqrs-and-event-sourcing), and [Event Sourcing](https://www.axoniq.io/concepts/cqrs-and-event-sourcing).

The message-driven nature of the framework becomes particularly useful when scaling the application or breaking it apart into distinct [microservice](https://www.axoniq.io/concepts/event-driven-microservices).
Furthermore, by Event Sourcing, you are future-proof to any shift and change of the models.

Both benefits come with their own set of requirements.
Firstly, we are inclined to use a distributed version of the `CommandBus`, `EventStore`, and `QueryBus` to break apart an application, considering their distinct routing requirements.
Secondly, as Event Sourcing requires us to store events forever, the event store will grow _indefinitely_.

[Axon Server](https://www.axoniq.io/products/axon-server) greatly simplifies these requirements by implementing these four requirements.
It is a dedicated message routing solution knowledgeable about the need to consistently route commands, stream events as fast as possible, and support the differing querying needs of each service.
But most of all, Axon Server is an event store, a database specifically designed for storing events for event sourcing purpose.
It offers superior scalability and throughput characteristics without requiring complex tuning of, for example, an RDBMS.

By using Axon Server in combination with Axon Framework, you will thus resolve the need to set up a distributed version of each bus and drop the requirement to optimize your event store by hand.

Be sure to visit the dedicated [Axon Server page](https://www.axoniq.io/products/axon-server) to learn more about all its capabilities and usages.
If desired, you can download it [here](https://www.axoniq.io/download) for free to give it a try.
And if you are curious about the additional features provided next to those described above, you can get a trial license by filling in [this](https://www.axoniq.io/axon-server-trial) form.

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

## AxonIQ Console

The Axon Framework team designed [AxonIQ Console](https://console.axoniq.io/) to further enable [Axon Framework](#axon-framework) applications with valuable data and tooling.

AxonIQ Console provides you with numerous benefits:
- [Event Processor](https://docs.axoniq.io/axon-framework-reference/latest/events/event-processors/) management tooling, like start, stop, [split, and merge](https://docs.axoniq.io/axon-framework-reference/latest/events/event-processors/streaming/#splitting-and-merging-segments)
- Automated monitoring of *all* your message handlers
- Insights into the flow of your messages with valuable diagrams
- The information required to deep-dive into the performance of your Axon Framework application

By doing all this, we aim to teach the inner workings of Axon Framework to any user, enabling you the get the most out of the framework.

If you want to know more about AxonIQ Console, you can check the product page [here](https://www.axoniq.io/products/axoniq-console) and the reference documentation [here](https://docs.axoniq.io/axoniq-console-reference/).
We refer you to "Legal Documents" in the bottom right corner of https://console.axoniq.io/ if you (and your team) are curious to understand how we secure all this behavior.

## Bill of Materials

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
