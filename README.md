# Basic knowledge

## DNS
- What is it?
The Domain Name System (DNS) is the phonebook of the Internet. Humans access information online through domain names, like nytimes.com or espn.com. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources.

- How does DNS work?
    - The process of DNS resolution involves converting a hostname (such as www.example.com) into a computer-friendly IP address (such as 192.168.1.1). An IP address is given to each device on the Internet, and that address is necessary to find the appropriate Internet device - like a street address is used to find a particular home. When a user wants to load a webpage, a translation must occur between what a user types into their web browser (example.com) and the machine-friendly address necessary to locate the example.com webpage.
## HTTP
### - What is it?

> The Hypertext Transfer Protocol (HTTP) is the foundation of the World Wide Web

- Is used to load web pages using hypertext links. HTTP is an application layer protocol designed to transfer information between networked devices and runs on top of other layers of the network protocol stack.
- A typical flow over HTTP involves a client machine making a request to a server, which then sends a response message.

### - HTTP Methods
> Also refered as HTPP Verbs, wich are: GET, POST, DELETE, PUT, HEAD, OPTIONS and PATCH. These methods are basically a category of operation on resources, so Not all resource have to support all methods. Based on our case and the characteristics of the resource, we can choose wich one do we use.

> The common features or group we can say, based on how these methods behaves while communicating are:

- SAFE: we can say a method is safe if the request doesn't alter the state of the server, so Read only operation are consider to be safe. So this type of method request shouldn't introduce any side effect or load on the server, also it shouldn't trigger ant external code.

- IDEMPOTENT: are the methods that no matter how many times you call the same request, you will get the same result.

- CACHEABLE: Response of the request that can be stored and used later. Not all the mothod responses can be cacheable. Ideally, a request that has both cacheable request and response code is elegible for caching.

- ### When should you use GET, POST, DELETE, PUT, etc… methods?
    - GET: When the client needs som kind of data or resource, he can request it with a GET method. This method is considered safe, idempotent and cacheable.
    - POST: To subbmit a resource we use the POST method, often causing a change in state or side effects on the server. So this method creates a new resource.
    - DELETE:This request deletes the specified resource. Its considered  an idempotent method becouse if you call a delete method a lot of times, the only resource that gets deleted is the first one, te subsequent ones are just a failed request.
    - PUT: Used to update or replace a resource with the requested payload. Its a idempotent method becouse calling it once or several times has no side effects.
    - HEAD: Similar to the GET method but this one only returns the header and not the body. Why you need this method at all then? Glad you ask, the reason its in the preformance. Ex: If we want to decide before downloading a large file, if the file its too large we dont want it. Here is when the HEAD method is nessesary, becouse the head can bring the size of the file. Like the GET method this one is safe, idempotent and cacheable method
    - OPTIONS:
    - PATCH: 
- When should you return an HTTP code 200, 201, 300, etc..?
        
## CORS
### - What is it?
>CORS (cross-origin resource sharing)

 - A request for a resource (like an image or a font) outside of the origin is known as a cross-origin request.
    - Unlike same-origin, navigating to "https://www.ejemplo.com/hola.html" from URL1 could be allowed with CORS. Allowing cross-origin requests is helpful, as many websites today load resources from different places on the Internet (stylesheets, scripts, images, and more).
    - Cross-origin requests, however, mean that servers must implement ways to handle requests from origins outside of their own. CORS allows servers to specify who (i.e., which origins) can access the assets on the server, among many other things.
## RESTful
### - What is it?
>RESTful web services
 - RESTful are built to work best on the Web. Representational State Transfer (REST) is an architectural style that specifies constraints, such as the uniform interface, that if applied to a web service induce desirable properties, such as performance, scalability, and modifiability, that enable services to work best on the Web. In the REST architectural style, data and functionality are considered resources and are accessed using Uniform Resource Identifiers (URIs), typically links on the Web. The resources are acted upon by using a set of simple, well-defined operations
### - Example
    
## Middlewares (On NodeJS)
- What is it?

- Example

## NPM, NVM and YARN
- What are those?

## JSON
- What is it?

- Example

- JSON Web Token
    - What is it?

    - Example

## Deploy a project
- How to?

- Examples of hosting

## Microservices
- What is it?

- Examples 

## Regular expressions
- What is it?

- Examples

## Minification
- What is it?

- Examples

## Ternary operator
- What is it? 
>

## Recursion
- What is it?
>
- Example
>

## Logical operators
- What is it?

- Examples

## Spread operator (...)
- What is it?
>
- Implementation
> 
- Examples
> 

# Version control system
- What is it?

## GIT
- What is it?

- Basic comands

## GitHub
- What is it?

- Basic comands

## GitFlow
- What is it?
  
# POO Basics

## Garbage collector
- What is it?
>

## Constructor/destructor
- What is it?
>

## Encapsulation
- What is it?
>

## Abstraction
- What is it?
>

# Markdown
- What is it?

- How to use it?

# Agile methodologies

## KANBAN
- What is it?
> 

## SCRUM
- What is it?
>

# Best practices

## Design patterns
- What is it?
>

## Testing
- What is it?
>
- Basic commands
> 
- Examples
> 

### Jest
- What is it?
>
- Basic commands
> 
- Examples
> 

## S.O.L.I.D
- What is it?
>

## D.R.Y
- What is it?
>

## K.I.S.S
- What is it?
>

## Codeparing
- What is it?
>

## Linter 
- What is it?
>
- Examples
    - ESLint

## Documentation 

### JSDoc 
- What is it?
>
- Examples
> 

### PlantUML
- What is it?
>
- Basic commands
> 
- Examples
> 

### Swagger
- What is it?
>
- Examples
> 

# Useful technologies
## Contentful

## Express

## Koa

## React

## Redux
   
## Vue.js

## Serverless

### AWS Lambda
- What is it?
>
- Implementation

> Note: Check of anothers

# Databases
## Relational DB
- What is it?
>
- Examples
    - SQL

## Non relational DB
- What is it?
>
- Basic commands
> 
- Examples
    - MongoDB:

## C.R.U.D operations
- What is it?
> 

## CouchDB
- What is it?
> 

## Redis
- What is it?
> 

# Node JS / JS Theory
          
## V8 engine
- What is it?
>

## Event loop
- What is it?
>

- Examples
>

## Modules, require, import/export
- What is it?
>
- Basic commands
> 
- Examples
> 

## Node eventemitter
- What is it?
>

## Streams 
- What is it?
> 
- Examples
> 

## Buffers
- What is it?
>
- Examples
> 

## JS Data types

##  Error handling
- What is it?
>
- Examples
> 

## Callback hell
- What is it?
>
- Examples
>

## Promises
- What is it?
>
- Basic commands
> 
- Examples
> 

## Async await
- What is it?
>
- Basic commands
> 
- Examples
> 

## HOF

### Arrow function
- What is it?
>
- Implementation
> 
- Examples
> 

### .map
- What is it?
>
- Implementation
> 
- Examples
> 

### .reduce
- What is it?
>
- Implementation
> 
- Examples
> 

### etc...

# Object methods

## this
- What is it?
>
- Implementation
> 
- Examples
> 

## keys
- What is it?
>
- Implementation
> 
- Examples
> 

## etc...

# Array methods

## .push
- What is it?
>
- Implementation
> 
- Examples
> 

## .pop
- What is it?
>
- Implementation
> 
- Examples
> 

## etc...

# JSON Methods

## stringify 
- What is it?
>
- Implementation
> 
- Examples
> 

## parse
- What is it?
>
- Implementation
> 
- Examples
> 

# SCOPE
## var
- What is it?
>
- Implementation
> 
- Examples
> 

## let
- What is it?
>
- Implementation
> 
- Examples
> 

## const
- What is it?
>
- Implementation
> 
- Examples
> 

# Ecmascript
- What is it?
>

# Prototype
- What is it?
>
- Implementation
> 
- Examples
> 

# Api
- What is it?
>
- Implementation
> 
- Examples
> 

## ApiGateway
- What is it?
>
- Implementation
> 
- Examples
> 



# Bibliography
```
https://javascript.info/
https://eloquentjavascript.net/
https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/get-started/README.md
https://github.com/bevacqua/es6
https://jgthms.com/javascript-in-14-minutes/
https://learnxinyminutes.com/docs/javascript/
https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9 

https://undraw.co/ (SVG Ilustration)
https://pages.github.com/
https://www.markdownguide.org/cheat-sheet/
```
