# Online food delivery application - Load Balancer Configuration

* Status: proposed
* Date: 2024-03-29

## Context and Problem Statement

Utilize AWS Elastic Load Balancer (ELB) to distribute incoming traffic across multiple instances of microservices deployed on Amazon EKS.

## Considered Options

* AWS ELB

## Decision Outcome

Chosen option: "AWS ELB", because 
###### High Availability:
 Elastic Load Balancer (ELB) automatically distributes incoming traffic across multiple instances of microservices deployed on Amazon EKS, ensuring high availability and fault tolerance of the application.

###### Scalability:
 ELB scales automatically to handle increasing levels of traffic, distributing the load evenly across available instances and preventing any single instance from being overloaded.

###### Health Checking: 
ELB performs health checks on backend instances and automatically routes traffic away from unhealthy instances, ensuring that only healthy instances receive requests.

###### Integration with AWS Services:
 ELB integrates seamlessly with other AWS services, such as Amazon EKS and Auto Scaling, allowing for easy integration and interoperability with existing AWS infrastructure components.
