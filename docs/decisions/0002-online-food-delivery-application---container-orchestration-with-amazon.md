# Online food delivery application - Container Orchestration with Amazon

* Status: proposed
* Date: 2024-03-29

## Context and Problem Statement

Deploy microservices using Amazon Elastic Kubernetes Service (Amazon EKS) for container orchestration.

## Considered Options

* ECS
* EKS

## Decision Outcome

Chosen option: "EKS", because EKS allows you to use Kubernetes, an open-source container orchestration platform. Kubernetes offers a high level of flexibility and portability, allowing you to deploy and manage containerized applications across different environments, including on-premises and other cloud providers.

### Positive Consequences

* Flexibility and Portability: EKS allows you to use Kubernetes, an open-source container orchestration platform. Kubernetes offers a high level of flexibility and portability, allowing you to deploy and manage containerized applications across different environments, including on-premises and other cloud providers.
* Rich Ecosystem: Kubernetes has a vast ecosystem of tools and resources, including monitoring, logging, networking, and security solutions. This ecosystem provides you with a wide range of options to enhance and customize your application deployment.
* Advanced Orchestration Features: Kubernetes offers advanced orchestration features such as automatic scaling, rolling updates, service discovery, and load balancing out of the box. These features can help you build a highly resilient and scalable application architecture.
* Community Support: Kubernetes has a large and active community, which means there are plenty of resources, documentation, and community-driven projects available to help you with your deployment. You can benefit from the collective knowledge and experience of the Kubernetes community.

### Negative Consequences

* Complexity: Kubernetes has a steep learning curve, especially for teams that are new to container orchestration and management. Setting up and managing Kubernetes clusters can be complex and require specialized knowledge and expertise.
* Cost: While EKS itself is a managed service provided by AWS, running Kubernetes clusters can incur additional costs, including compute resources, storage, and network bandwidth. Optimizing and managing these costs effectively requires careful planning and monitoring.
