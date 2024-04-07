# Online food delivery application - Choosing Backend Technology

* Status: proposed
* Date: 2024-04-07

## Considered Options

* Python
* Node.js

## Decision Outcome

Chosen option: "Node.js", because If real-time updates and notifications are essential features of the online food delivery application, Node.js's event-driven architecture and support for asynchronous operations make it better suited for handling these requirements compared to Python.

### Positive Consequences

* Simplicity and Productivity: If rapid development and iteration cycles are priorities for the project, Node.js's simplicity and ease of use can accelerate the development process. JavaScript's ubiquity and the availability of lightweight frameworks like Express.js make it easy for developers to get started quickly and build features iteratively.
* Handling Concurrent Requests: Online food delivery applications often need to handle multiple concurrent requests from users placing orders, tracking deliveries, and updating preferences. Node.js's non-blocking I/O model enables it to handle these concurrent requests efficiently, ensuring a responsive user experience.
* Scalability Requirements: If the online food delivery application is expected to scale rapidly and handle a large number of users and transactions, Node.js's scalability and performance characteristics make it a suitable choice for meeting these requirements.
* Full-Stack Development: With Node.js, developers can use JavaScript for both server-side and client-side development, enabling full-stack development with a consistent language and toolset. This can streamline development workflows and reduce the learning curve for building and maintaining the application.

### Negative Consequences

* Complexity: While Node.js simplifies I/O-bound operations, building complex, CPU-intensive applications with Node.js can be challenging. Online food delivery applications with intricate business logic, complex data processing requirements, or heavy backend processing may require additional effort to implement and maintain effectively.
* CPU-Intensive Tasks: Node.js's single-threaded event loop model is not well-suited for CPU-intensive tasks that block the event loop, such as heavy computation or image processing. 
