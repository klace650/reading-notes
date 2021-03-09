# Authentication:

1. Explain what a “Singleton” is (in Computer Science terms)  

- "...a pattern that restricts the instatnition of a class to one object"
[source](https://www.sitepoint.com/javascript-design-patterns-singleton/)

Keeps from firing off more than one thing to the things don't get all jammed up in things.

2. Explain how the Singleton pattern can be used with Node modules, specifically with classes  

The singleton pattern can be used with classes to instantiate multipul instances of the same object with out messing up the orginal instance. Instead of calling to the same instance - singleton will make a dang ol copy.

3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?  

I'd probably use a singleton? 

## Now about some words:

Router Middleware - this is the process of changing the request/response. Sort of intercepts between req and res =>  `req, middleware, res`

- **Dynamic Module Loading** - "returns a promise the resolves into a module object that contains all its exports"[source](https://javascript.info/modules-dynamic-imports)  
- **Singleton Pattern**  - used to instanicate an object multipule times witout ruining everything.
- **CRUD -> REST Method Matches**   
Create = PUT  
Read = READ  
Update = PUT  
Delete = DELETE  
- **Mock Testing** - method used in jest to mock a callback function for testing.

