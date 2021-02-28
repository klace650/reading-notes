# Reading Notes - Class 03

## Name 3 real world use cases where you’d want to change the request with custom middleware  
1. Login auth
2. WRRC
3. Loggers

[Source](https://medium.com/@selvaganesh93/how-node-js-middleware-works-d8e02a936113)

## True or false: The route handler is middleware?  

Falsey

[Source](https://stackoverflow.com/questions/58925276/what-is-the-difference-between-a-route-handler-and-middleware-function-in-expres#:~:text=They%20are%20not%20middleware%20functions,the%20only%20one%20callback%20function)

## In what ways can a middleware function end the process and send data to the browser?  

When its all done running or there is an error.

## At what point in the request lifecycle can you “inject” middleware?
Whenever you need to?
[SOURCE](https://www.npmjs.com/package/express-inject-middleware);

## What can cause express to error with “Request headers sent twice, cannot start a second response”

It means there was an error that wasn't caught and the code moved on to another request.


# Terms:
- Middleware : 

- Request Object : This is the object sent from the user request

- Response Object : this is what the server sends back to the user

- Application Middleware : middleware used within the app - ex. error handlers.

- Routing Middleware  : this is middleware that is responsible for routing the request and responses.

- Test Driven Devlopment : this is the practice of using testing first to ensure your code behaves as expected.

- Behavioral Testing : uses human readable language to describe and test the aspects of what the human using it cares about.

[Source](https://medium.com/@connecttokc/behaviour-driven-testing-in-node-js-using-mocha-chai-5e0c85258bbe])