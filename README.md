# stream-bridge-publish-subscribe
This repository contains Java Spring Boot microservices built with REST APIs that utilize Spring Cloud Stream and StreamBridge.

This repository contains Java Spring Boot microservices built with REST APIs that utilize Spring Cloud Stream and StreamBridge for asynchronous communication through messaging systems (e.g., Apache Kafka or RabbitMQ).

Key Features:
StreamBridge Publisher:
Publishes messages dynamically to defined bindings or topics using Spring Cloud Stream’s StreamBridge.
Enables decoupled and scalable event-driven architecture.
Ideal for use cases like sending events after user actions, data changes, or integrations.
Message Subscriber (Consumer):
Listens to incoming messages from bound topics or queues.
Processes the received data for further business logic or persistence.
Supports concurrent message consumption and fault tolerance.
Spring Boot REST APIs:
Provides HTTP endpoints to trigger message publishing, fetch results, or manage data.
Follows clean RESTful design principles for easy integration.

Tech Stack:
Java 17+
Spring Boot
Spring Cloud Stream
StreamBridge
Apache Kafka / RabbitMQ (pluggable binders)
REST APIs
Maven

This architecture enables event-driven communication between microservices with minimal coupling, supporting scalability, flexibility, and resilience in modern distributed systems.
