# Online food delivery application - Message queue systems

* Status: proposed
* Date: 2024-03-29

## Context and Problem Statement

Adopt a Message queue systems for the online food ordering app.

## Considered Options

* kafka
* RabbitMQ
* Self-developed

## Decision Outcome

Chosen option: "kafka", because ######  Event Streaming:
Perfect for data intensive and event streaming scenarios

###### Scalability:
 Kafka is known for its scalability, allowing you to handle high message throughput and large volumes of data with ease.

###### Decoupling:
Kafka's decoupled architecture allows producers and consumers to operate independently, enabling better resilience and fault tolerance. 

######  Community Adoption: 
Kafka has gained widespread adoption in the industry, with many large-scale deployments in production environments. This means there's a wealth of community knowledge, resources, and support available, which can be beneficial when building and maintaining your application.

### Positive Consequences

* Scalability: Kafka is highly scalable, allowing you to handle large volumes of data and high throughput. This scalability is essential for applications like online food delivery, where there's a need to process a significant number of orders and updates in real-time.
* Scalability: Kafka is highly scalable, allowing you to handle large volumes of data and high throughput. This scalability is essential for applications like online food delivery, where there's a need to process a significant number of orders and updates in real-time.
* Fault Tolerance and Durability: Kafka provides strong durability guarantees by persisting messages to disk, ensuring that messages are not lost even in the event of system failures. This ensures data integrity and reliability, which are critical for online food delivery applications where order data must be preserved.

### Negative Consequences

* Complexity: Implementing Kafka in a microservices architecture can introduce complexity, especially if your team is not familiar with Kafka or event-driven architectures. Managing Kafka clusters, configuring topics, and ensuring data consistency can be challenging tasks.
* Learning Curve: Kafka has a learning curve, particularly for developers who are new to event-driven architectures or distributed systems. 
