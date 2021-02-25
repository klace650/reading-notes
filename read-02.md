# Reading Notes - Class 02

## What’s the difference between PUT and PATCH?  
*PUT*
- Is a method that is used to change the entire resource being requested by the user. 
- Like POST because it can create resources.
- Overwrites entire entity or creates a new one.  

*PATCH*  
- Updates partial to resources.
- Only need to send the data thats being updated  
- Won't change anything else  

*source - https://rapidapi.com/blog/put-vs-patch/*

## Provide links to 3 services or tools that allow you to “mock” an API for development like json-server  
1. https://www.mock-server.com/
2. https://www.postman.com/
3. https://www.npmjs.com/package/json-server


## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?  

**Swagger**
- Is a set of rules (specfication) that help format API docs.
- Human readable and Computer Readable
- Makes docs easier to read across thew board  
*https://swagger.io/*
*https://swagger.io/specification/*

**API DOC**
- Also used to help with docs - works in line though
- Tracks version numbers with changes.

*https://apidocjs.com/*  
*https://apidocjs.com/example/*

## Compare and contrast SOAP and ReST

- Both are web service commiuncation protocols
- REST is most common
- SOAP used to be the best

**SOAP**

- Simple Object Access Protocol
- Processes operations in a standard set of message patterns.  

**REST**  

- Representational State Transfer
- Consistent interface to access names resources
- Accesses data

*https://stackify.com/soap-vs-rest/*  

# Terms:

- Web Server: Control how web users access files - uses HTTP probably, understands URL, can be accessed by domain names, serves files to end users.  
*https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server*

- Express: Is a web framework that is super simple and light and provides a lot of built in middleware and methods. 
- Routing: This is how websites/apps function, the routes are connected to some code and is executed when those routes are requested by the user.  
*https://medium.com/@wilbo/server-side-vs-client-side-routing-71d710e9227f*
- WRRC: Web Response Request Cycle - this is the process of taking a request from a user, sending it to a server, and recieving and viewing the response from the server.