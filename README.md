# Basic knowledge

## DNS

Domain name system, is like the phonebook of the internet, they are responsible of finding the IP’s of every web site.

In a typical DNS query without any caching, there are four servers that work together to deliver an IP address to the client: recursive resolvers, root nameservers, TLD nameservers, and authoritative nameservers.

First the resolver queries the root nameserver. The root server is the first step in translating (resolving) human-readable domain names into IP addresses. The root server then responds to the resolver with the address of a Top Level Domain (TLD) DNS server (such as .com or .net) that  stores the information for its domains.

Next the resolver queries the TLD server. The TLD server responds with the IP address of the domain’s authoritative nameserver. The recursor then queries the authoritative nameserver, which will respond with the IP address of the origin server.

The resolver will finally pass the origin server IP address back to the client. Using this IP address, the client can then initiate a query directly to the origin server, and the origin server will respond by sending website data that can be interpreted and displayed by the web browser.



## HTTP

Hyper text transfer protocol, basically it’s a protocol to connect between clients and servers, where the client sends a request, and the server returns a response to that request.

Methods for HTTP are: POST – GET – PUT – PATCH – DELETE
POST → Is a rquest to the web server to accept the data enclosed in the body of the request. Used more likely to store some new data.

GET → Is used to read data from the URL.

PUT → used to update or create new data, where the resource ID is chosen by the client and not the server.

DELETE → Used to delete a resource.
        
## CORS

A request for a resource (like an image or a font) outside of the origin is known as a cross-origin request. CORS (cross-origin resource sharing) manages cross-origin requests.

Allowing cross-origin requests is helpful, as many websites today load resources from different places on the Internet (stylesheets, scripts, images, and more).

## RESTful

A RESTful API is an architectural style for an application program interface (API) that uses HTTP requests to access and use data. That data can be used to GET, PUT, POST and DELETE data types, which refers to the reading, updating, creating and deleting of operations concerning resources.

REST technology is generally preferred over other similar technologies. This tends to be the case because REST uses less bandwidth, making it more suitable for efficient internet usage. RESTful APIs can also be built with programming languages such as JavaScript or Python.

Example → https://official-joke-api.appspot.com/jokes/programming/random

This API REST will return you in JSON format, a random joke.
    
## Middlewares (On NodeJS)

It’s the code that runs between the request from the client, until it reaches the server.

A perfect example is when you need to allow a user to have access to a determinate URL, and if he’s not logged in, it will return you to a different URL than the requested one.

## NPM, NVM and YARN

NPM → is the package manager for the node JavaScript platform. It puts modules in place so node can find them.

NVM → Is a tool that allows you to install nodejs and have different version of it.

YARN → is a package manager for your code. It allows you to share your code to another developers around the world.

## JSON

JavaScript Object Notation → When exchanging data with the server, the data can only be text, and JSON is text, and we can convert every JavaScript object into JSON and send it to the server.

Sending Data →



Recieving data → 



JSON is a lightweight data-interchange format
JSON is "self-describing" and easy to understand
JSON is language independent *

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
