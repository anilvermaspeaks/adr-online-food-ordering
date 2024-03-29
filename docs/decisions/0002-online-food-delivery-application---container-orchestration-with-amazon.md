# Online food delivery application - Container Orchestration with Amazon

* Status: proposed
* Date: 2024-03-29

## Context and Problem Statement

Deploy microservices using Amazon Elastic Kubernetes Service (Amazon EKS) for container orchestration.

## Considered Options

* ECS
* EKS

## Decision Outcome

Chosen option: "EKS", because ECS offers tight integration with AWS services and can be easier to use within the AWS ecosystem, it's not as portable as EKS. On the other hand, EKS is ideal for scenarios where portability across different environments is essential.
