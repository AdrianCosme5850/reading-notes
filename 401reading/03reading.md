# Express REST API  

## ES6 Classes 

1. Classes are templates for creating objects.  
2. Classes cannot be hoisted, they must be defined before they are used.  
3. A constructor is a framework for creating one of these objects. This is used to refer to the overall object as itself.  

## Using Express Routing  

1. It refers to how the application will respond to user requests.  
2. Method refers to one of the HTTP methods. A route path defines what endpoint the method uses.  
3. Next can be used for middleware, or to pass an error to an error handler. You must call next in your middleware, otherwise the code will be stuck waiting to execute something else.  

## Express routing  

1. An Express Router is like a mini-Express application that provides routing APIs.  
2. router.use makes the server use our express router.  
3. Routes can use middleware for things like searching for parameters and throwing errors when there isn't one.  
