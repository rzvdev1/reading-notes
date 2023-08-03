# Event Driven Applications

What native Node.js module allows us to get started with Event Driven Programming?
The native Node.js module that allows us to get started with Event Driven Programming is the EventEmitter module.

```
const EventEmitter = require('events').EventEmitter;
const myEventEmitter = new EventEmitter;
```

What is the value of Object Oriented Programming used in tandem with Event Driven Programming?
The value of Object Oriented Programming used in tandem with Event Driven Programming is the emit method.

```
eventEmitter.emit('start');
```

Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.

Event Driven Programming is useful on the backend using Node.js because it allows us to create a server that listens for events and then responds to those events. By this, I mean that we can create a server that listens for a request from a client and then responds to that request with the appropriate response. For example a client is requesting a webpage from a server like google search of space facts , the server will listen for that request and then respond with the appropriate webpage that the client requested about space facts.

## Reflection

Looking ahead at this module’s course schedule, I look forward to learning about the following:

- Event Driven Programming in Node.js
- Data structures and Algorithms on Queue with two stacks, Balanced Brackets, Stack Max, and Trees Implementation
- Network Events

My goals after reading and reviewing the class README are understanding the following:

- EventEmitter module
- Emit method
- Integration of SQL for event driven programming
- Use modules to emit events

### Resources I use

Event-Driven Programming in Node.js[^1]

[^1]: [Event-Driven](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)
