# Django Rest Framework
Reference Book: [ Django For APIS](https://djangoforapis.com/) by William S. Vincen

# Chapter-1: Web APIs

While a monolithic application is a single unified unit, a microservices architecture breaks it down into a collection of smaller independent units

### Monolithic Architecture
` Complexity: Difficult to decouple and isolate different parts of the application, and even to fully understand all of the application’s components.`

`Scalability: Monolithic software applications can only be scaled as a single unit. This makes it difficult or impossible to fine-tune the resources that each component of the application uses.`

`Legacy technology: Adding new technologies to a monolithic software application can be extremely challenging.`

### Microservices
` Scalability: Microservices applications are tremendously scalable, since each component can be scaled independently of the rest.`

`Independence: Each component in a microservices architecture is independent of the others, with communication happening via an API gateway. Bugs and crashes in one component don’t bring down the rest of the application.`

`Flexibility: Monolithic software applications have a single code base and operate as a single unit, so they need to select a single programming language and tech stack that may not be optimal for the entire application.`

### URLs
`A URL (Uniform Resource Locator) is the address of a resource on the internet. For example, the
Google homepage lives at https://www.google.com.`


Every URL has three potential parts:
- a scheme
- a hostname
- and an (optional) path

### HTTP
`Every HTTP message consists of a status line, headers, and optional body data`

REpresentational State Transfer (REST) is an architecture first proposed in 2000 by Roy Fielding.

Every RESTful API:
- is stateless, like HTTP
- supports common HTTP verbs (GET, POST, PUT, DELETE, etc.)
- returns data in either the JSON or XML format

<br><br>

# Chapter 2: Library Website and API
