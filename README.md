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
> Also refered as HTPP Verbs, wich are: GET, POST, DELETE, PUT, HEAD, OPTIONS and PATCH. These methods are basically a category of operation on resources.

> The common features or group we can say, based on how these methods behaves while communicating are:

- SAFE: we can say a method is safe if the request doesn't alter the state of the server.This type of method request shouldn't introduce any side effect or load on the server, also it shouldn't trigger ant external code.

- IDEMPOTENT: are the methods that no matter how many times you call the same request, you will get the same result.

- CACHEABLE: Response of the request that can be stored and used later.

- ### When should you use GET, POST, DELETE, PUT, etc… methods?
    - GET: When the client needs som kind of data or resource, he can request it with a GET method. This method is considered safe, idempotent and cacheable.
    - POST: This method creates a new resource.
    - DELETE: This request deletes the specified resource. 
    - PUT: Used to update or replace a resource with the requested payload. Its a idempotent method becouse calling it once or several times has no side effects.
    - HEAD: Similar to the GET method but this one only returns the header and not the body. Like the GET method this one is safe, idempotent and cacheable method
    - OPTIONS:
    - PATCH: 
- When should you return an HTTP code 200, 201, 300, etc..?

## CORS
- ### What is it?
>CORS (cross-origin resource sharing)

 - A request for a resource (like an image or a font) outside of the origin is known as a cross-origin request.
    - Unlike same-origin, navigating to "https://www.ejemplo.com/hola.html" from URL1 could be allowed with CORS. Allowing cross-origin requests is helpful, as many websites today load resources from different places on the Internet (stylesheets, scripts, images, and more).
## RESTful
- ### What is it?
>Restful is a software architectural style for applications based on networks (like Internet).
- ### Example
    https://official-joke-api.appspot.com/jokes/programming/random
    This is a public API implemented as RESTful web service. Your browser will show an awful JSON-formatted programming joke.
## Middlewares (On NodeJS)
- What is it?
A Middleware is a program, function or script that is going to run, between the time that the server gets the request, and the time that te server sends out the response to the client.  
- Example
```
var myLogger = function (req, res, next) {
  console.log('LOGGED');
  next();
};

```
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
