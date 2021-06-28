## Express REST API


1. **Name 3 real world use cases where you’d want to change the request with custom middleware**

      - ***adding current server time to the request***
      - ***override the post method to put or delete***
      - ***encrypt secure data***

2.  **True or false: The route handler is middleware?**

     ***If the router handler has 'next' argument it's considered as middleware, otherwise it's just a route handler.***


3. **In what ways can a middleware function end the process and send data to the browser?**

      - ***By calling "next" using parameter***
      - ***by Throwing an error***


4. **At what point in the request lifecycle can you “inject” middleware?** 

      ***You can inject many middleware as you want as long as you don't reach the route handler.***


5. **What can cause express to error with “Request headers sent twice, cannot start a second response”**

    ***when trying to send a header after some of the body has already been written. For example, callbacks that are accidentally called twice.***



- **Middleware:**  *function that executes during the lifecycle of a request to the Express server,and has access to the HTTP request and response for each route (or path) it’s attached to.*

- **Request Object:** *is one half of the request and response cycle to examine calls from the client side, make HTTP requests, and handle incoming data whether in a string or JSON object.*

- **Response Object:** *is one half of the request and response cycle to send data from the server to the client-side through HTTP requests.*

- **Application Middleware:** *a middleware that bound to an instance of express, using app.use() and app.VERB()*

- **Routing Middleware:** *a middleware that bound to an instance of express.Router().*

- **Test Driven Development:**  *is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. Behavioral Testing: is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.*


1. **Which 3 things had you heard about previously and now have better clarity on?**

    -  ***routing handler***
    -  ***middleware***
    -  ***request and response objects***

2. **Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

    -  ***routing handler***
    -  ***middleware***
    -  ***request and response objects***

3. ***What are you most excited about trying to implement or see how it works?***

    *testing units for REST API server*


## Review: ES6 Classes

  ***Classes are a template for creating objects. They encapsulate data with code to work on that data. Classes in JS are built on prototypes but also have some syntax and semantics that are not shared with ES5 class-like semantics.***


 ## Using Express Routing

  ***Routing refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routing, see Basic routing.**

  ***You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests. For a full list, see app.METHOD. You can also use app.all() to handle all HTTP methods and app.use() to specify middleware as the callback function (See Using middleware for details).***

  ***These routing methods specify a callback function (sometimes called “handler functions”) called when the application receives a request to the specified route (endpoint) and HTTP method. In other words, the application “listens” for requests that match the specified route(s) and method(s), and when it detects a match, it calls the specified callback function.***


## Express Routing 

  ***With the inclusion of the Express 4.0 Router, we are given more flexibility than ever before in defining our routes. To recap, we can:***

   - *Use express.Router() multiple times to define groups of routes*
   - *Apply the express.Router() to a section of our site using app.use()*
   - *Use route middleware to process requests*
   - *Use route middleware to validate parameters using .param()*  
   - *Use app.route() as a shortcut to the Router to define multiple requests on a route*
