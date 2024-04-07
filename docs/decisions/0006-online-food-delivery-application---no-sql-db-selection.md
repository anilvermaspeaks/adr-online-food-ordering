# Online food delivery application - No-SQL DB Selection

* Status: proposed
* Date: 2024-04-02

## Context and Problem Statement

Choose NoSQL DB to store user/restaurant data

## Considered Options

* MongoDB
* Cassandra

## Decision Outcome

Chosen option: "Cassandra", because Geo-Distribution Support: Online food delivery services often operate in multiple geographic regions. Cassandra's support for multi-region and geo-distributed deployments allows data to be replicated across different data centers, ensuring data locality, disaster recovery, and compliance with regulatory requirements.

Cassandra's flexible data model accommodates dynamic and evolving data schemas, which is advantageous for applications with changing requirements. Online food delivery applications may need to store various types of data, such as customer profiles, order information, and delivery status updates.

### Positive Consequences

* Cassandra's flexible data model accommodates dynamic and evolving data schemas, which is advantageous for applications with changing requirements. Online food delivery applications may need to store various types of data, such as customer profiles, order information, and delivery status updates.
* High Availability: In an online food delivery application, downtime can lead to lost orders and dissatisfied customers. Cassandra's distributed architecture and built-in replication features ensure high availability and fault tolerance. Even in the event of node failures or network partitions, Cassandra continues to provide access to data, minimizing service disruptions.
* Scalability: Cassandra is renowned for its linear scalability, making it an excellent choice for applications requiring high availability and massive scalability. Online food delivery applications often experience rapid growth in both user base and data volume. Cassandra's ability to distribute data across multiple nodes while maintaining performance ensures that the application can scale seamlessly to accommodate increasing demand.
* Tunable Consistency Levels: Cassandra offers tunable consistency levels, allowing developers to balance consistency, availability, and partition tolerance according to application requirements. This flexibility is beneficial for online food delivery applications where maintaining strong consistency across distributed data is challenging but eventual consistency is acceptable for certain use cases.

### Negative Consequences

* Complexity: Cassandra has a steep learning curve, especially for developers who are new to NoSQL databases or distributed systems. Setting up and managing Cassandra clusters requires careful planning, configuration, and monitoring to ensure optimal performance and reliability.


* Operational Overhead: Running and maintaining Cassandra clusters involves ongoing operational tasks such as cluster provisioning, monitoring, scaling, and backup and recovery. Managing these tasks can add complexity and overhead to your operations, especially for smaller teams with limited resources.
