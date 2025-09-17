# REST API 

A REST API (Representational State Transfer Application Programming Interface) is a set of rules and conventions for building and interacting with web services. It allows different software applications to communicate with each other over the internet using standard HTTP protocols (like GET, POST, PUT, DELETE, CREATE, UPDATE).

- Think of it as a menu in a restaurant:

i. You (the client) are given a menu (the API documentation)

ii. You order an item from the menu (send a request)

iii. The kitchen (the server) prepares the dish and serves it to you (sends a response)

- Key Features (REST Principles)

REST APIs are defined by six guiding constraints:

i. Stateless: Each request from a client to the server must contain all the information needed to understand and process the request. The server does not store any session data about the client between requests.

ii. Client-Server: The client and server are separate entities that evolve independently. The client is responsible for the user interface, and the server is responsible for processing and storing data.

- Uniform Interface: This is the core of REST. It simplifies architecture by ensuring a standardized way of communicating. This includes:

i. Using resources (like /users or /products) as unique identifiers (URIs).

ii. Representations of data (like JSON or XML) to exchange information.

- Cacheable: Responses from the server must define themselves as cacheable or not. This improves performance and scalability on the client-side.

- Layered System: The architecture can be composed of multiple layers (e.g., security, load balancing). The client cannot tell if it is connected directly to the end server or to an intermediary.

- Code on Demand (optional): The server can temporarily extend client functionality by sending executable code (like JavaScript). This is the least used constraint.



## HTTP RESTful clients


1. AXIOS is a promise based HTTP client for the browser and node.js, and depends on a native ES6 Promise implementation


2. GraphQL - GraphQL is an application layer query language that interprets a string by a server, which then returns the required data in a specified format.
The response format is described in the query and defined by the client instead of the server. They are called client‐specified queries.

3. To execute any of the applications, first run mpm install where you find package.json file.



