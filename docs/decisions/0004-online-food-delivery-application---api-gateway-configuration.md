# Online food delivery application - API Gateway Configuration

* Status: proposed
* Date: 2024-03-29

## Context and Problem Statement

Configure AWS API Gateway as the entry point for all client requests, routing them to the appropriate microservices based on predefined API routes.

## Considered Options

* AWS API Gateway

## Decision Outcome

Chosen option: "AWS API Gateway", because 
###### Centralized Management: 
AWS API Gateway provides centralized management of APIs, allowing for easy configuration, monitoring, and versioning of API endpoints.
###### Security:
 API Gateway offers built-in features for authentication, authorization, and access control, ensuring that only authenticated and authorized users can access the application's APIs.
###### Scalability: 
API Gateway scales automatically to handle varying levels of API traffic, ensuring that the application can handle high volumes of requests without degradation in performance.
Integration with AWS Services: API Gateway integrates seamlessly with other AWS services, such as Lambda functions and AWS Cognito, allowing for easy integration and interoperability with existing AWS infrastructure components.
