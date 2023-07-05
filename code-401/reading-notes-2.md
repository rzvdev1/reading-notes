# Express, NPM, TDD, CI/CD

Explain middleware, answer as though I were a non-technical recruiter.

- Middleware is a function that has access to the request and response objects. Its going to run between the time a server gets a request and the time before it sends a response back.

Express the most popular web framework. Express is “unopinionated”, because you can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one file or multiple files, and using any directory structure.

What is a module and why is modularity useful to us as developers?
A module is a JavaScript library/file that you can import into other code using Node's require() function. Modularity is useful because it allows us to break up our code into smaller pieces that are easier to maintain and debug.

The version of npm on my machine is 9.7.2. The command to install a library/package called ‘jshint’ is npm i jshint.

TDD is Test-driven development refers to a style of programming in which three activities are tightly interwoven: coding, testing and design.

The test are important because they help us to find error in our code. They also help us to make sure that our code is working the way we want it to.

The three expected benefits of testing are:

1. many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
2. the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
3. although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
The 2 individual pitfalls forgetting to run tests frequently & writing tests that are too large or coarse-grained are and the 2 team pitfalls are poor maintenance of the test suite & abandoned test suite.

The three benefits of Continuous Integration are that it allows for faster feedback, it allows for better quality software, and it allows for more visibility.
Continuous Delivery is a software development practice where code changes are automatically prepared for a release to production. Continuous Deployment is a software development practice where code changes are automatically deployed to production.
GitHub is a website that allows developers to collaborate on projects together which uses CI/CD.

## Reflection

## Things I want to know more about

1. ?

### Resources I use

NodeJS and Express[^1], NPM[^2], TDD[^3], CI/CD[^4]

[^1]: [Node JS](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
[^2]: [NPM](https://docs.npmjs.com/about-npm)
[^3]: [TDD](https://www.agilealliance.org/glossary/tdd/)
[^4]: [CI/CD](https://www.youtube.com/watch?v=k2aNsQKwyOo&themeRefresh=1)
