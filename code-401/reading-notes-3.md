# Express REST API

Review: ES6 Classes

Classes are a template for creating objects. A class declaration has same temporal dead zone restrictions as let or const and behave as if they are not hoisted. A constructor is like a default template like a doc files that has a layout ffor you to use and contextual “this” means the current item within the constructor.

The routing refers to how an application’s endpoints (URIs) respond to client requests. The difference between app.get('/data/:id') and app.get('/data/:name') is that the first one is looking for a specific id and the second one is looking for a specific name.

A route path is with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions. and a route method is derived from one of the HTTP methods, and is attached to an instance of the express class. It is appropriate to add next as a parameter to a route handler when impose pre-conditions on a route, then pass control to subsequent routes if there’s no reason to proceed with the current route. If next has been passed to your middleware as a parameter you must call next() to pass control to the next middleware function.

A Express Router is like a mini-Express application without all the bells and whistles of an express application, just the routing stuff. We initialize express.Router() in an express server by using app.use() and passing in the router as the callback function. We can then define routes on the router object instead of on the app object.

We use route middleware to do something before a request is processed. This could be things like checking if a user is authenticated, logging data for analytics, or anything else we’d like to do before we actually spit out information to our user.

## Reflection

What are your learning goals after reading and reviewing the class README?

### Resources I use

ES6 Classes[^1], Express Routing[^2] and New Router in ExpressJS 4.0[^3]

[^1]: [ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
[^2]: [Express](https://expressjs.com/en/guide/routing.html)
[^3]: [ExpressJS 4.0](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)
