# Online food delivery application - Message queue systems

* Status: proposed
* Date: 2024-03-29

## Context and Problem Statement

Adopt a Message queue systems for the online food ordering app.

## Considered Options

* kafka
* RabbitMQ

## Decision Outcome

Chosen option: "RabbitMQ", because ###### Loose Coupling: 
RabbitMQ decouples microservices by providing a message-based communication mechanism, allowing services to communicate asynchronously without direct dependencies on each other.

###### Scalability:
 RabbitMQ supports distributed messaging and message queuing, enabling scalable and fault-tolerant communication between microservices, even under high load conditions.

###### Reliability:
 RabbitMQ ensures reliable message delivery by providing features such as message acknowledgments, persistent message storage, and message retry mechanisms, minimizing the risk of message loss or duplication.
