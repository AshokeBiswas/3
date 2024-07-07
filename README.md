Q1. What is an API? Give an example, where an API is used in real life.
API (Application Programming Interface) is a set of rules and protocols that allow different software applications to communicate with each other. It defines methods and data formats that applications can use to request and exchange information.

Example: A common real-life example of an API is the Google Maps API, which allows developers to embed Google Maps on web pages and mobile applications. This API provides various functionalities, such as displaying maps, adding markers, and calculating routes, enabling developers to integrate Google Maps services into their own applications.

Q2. Give advantages and disadvantages of using API.
Advantages:

Integration: Allows different systems and applications to communicate and work together seamlessly.
Efficiency: Facilitates faster development by enabling developers to leverage existing functionalities and services.
Scalability: Helps in building scalable applications by allowing functionalities to be divided into modular components.
Automation: Enables automation of tasks by allowing applications to interact programmatically.
Data Sharing: Allows data to be easily shared between different systems, improving data accessibility and consistency.
Disadvantages:

Security: APIs can expose vulnerabilities and be targeted by malicious attacks if not properly secured.
Complexity: Can add complexity to the development process, especially when integrating multiple APIs.
Dependency: Applications can become dependent on third-party APIs, leading to potential issues if the API changes or becomes unavailable.
Maintenance: Requires ongoing maintenance to ensure compatibility with changes in the API or the services it connects to.
Performance: Can introduce latency and performance bottlenecks, especially if the API calls are slow or the network is unreliable.
Q3. What is a Web API? Differentiate between API and Web API.
Web API is a specific type of API that is accessed over the web using HTTP/HTTPS protocols. It allows web-based applications to interact with each other and exchange data over the internet.

Differences between API and Web API:

API:

General term for any set of rules and protocols that enable software applications to communicate.
Can be used for various types of interactions, including library APIs, operating system APIs, and service APIs.
Not necessarily accessed over a network.
Web API:

A specific type of API that is accessed over the web using HTTP/HTTPS.
Typically used to enable communication between web servers and clients or between web-based applications.
Examples include RESTful APIs and SOAP APIs.
Q4. Explain REST and SOAP Architecture. Mention shortcomings of SOAP.
REST (Representational State Transfer):

Architecture: An architectural style for designing networked applications. It relies on a stateless, client-server, cacheable communications protocol, typically HTTP.
Principles:
Stateless: Each request from a client to the server must contain all the information needed to understand and process the request.
Client-Server: The client and server operate independently, and the interface between them is uniform.
Cacheable: Responses must define themselves as cacheable or not to prevent clients from reusing stale or inappropriate data.
Uniform Interface: A standardized way to interact with resources, typically through CRUD (Create, Read, Update, Delete) operations.
Shortcomings:
Less suited for complex transactions and operations.
Lack of formal contracts between client and server.
SOAP (Simple Object Access Protocol):

Architecture: A protocol for exchanging structured information in web services using XML. It is platform and language-independent.
Principles:
Strictly defined standards for message structure, encoding rules, and conventions.
Operates over any transport protocol, including HTTP, SMTP, and more.
Uses WSDL (Web Services Description Language) for defining service endpoints and operations.
Shortcomings:
Complexity: More complex and heavyweight compared to REST.
Performance: Slower due to extensive use of XML and the need for parsing.
Flexibility: Less flexible and harder to implement for simple services.
Learning Curve: Steeper learning curve due to strict standards and specifications.
Q5. Differentiate between REST and SOAP.
Feature	REST	SOAP
Protocol	Architectural style using HTTP	Protocol with strict standards using XML
Message Format	Typically JSON or XML	XML
Transport	Primarily HTTP/HTTPS	Can use HTTP, SMTP, TCP, etc.
State	Stateless	Stateful or stateless
Operations	CRUD operations mapped to HTTP methods (GET, POST, etc.)	Custom operations defined in WSDL
Performance	Generally faster and more lightweight	Generally slower due to XML parsing
Security	Relies on underlying transport security (e.g., HTTPS)	Built-in security features (WS-Security)
Flexibility	More flexible and easier to implement for simple services	More rigid and complex
Standards	No strict standards	Strict standards and specifications
Use Cases	Best for web-based, resource-oriented services	Best for enterprise-level, transactional services
These differences highlight how REST is often preferred for web-based and simpler services due to its flexibility and ease of use, while SOAP is chosen for more complex, enterprise-level applications that require strict standards and advanced security features.
