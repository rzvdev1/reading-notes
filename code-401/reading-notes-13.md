# Socket.io Chat Example

The chat example is a simple chat app that allows users to connect to a server and send messages to each other. The server is able to broadcast messages to all connected clients. For example a chat app that allows users to send messages to each other like messenger or slack. The proof is life we are getting is that the server is listening for a connection and when a connection is made it will console log a message saying that a user has connected. It will also console log a message when a user disconnects. Example :

```
io.on('connection', (socket) => {
  console.log('a user connected');
  socket.on('disconnect', () => {
    console.log('user disconnected');
  });
});
```

The flag that you would use is the broadcast flag. Example:

```
io.emit('some event', { someProperty: 'some value', otherProperty: 'other value' }); // This will emit the event to all connected sockets
```

```
io.on('connection', (socket) => {
  socket.broadcast.emit('hi');
});
```

# Rooms

A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.
You can join a room by using the join method. Example:

```
io.on("connection", (socket) => {
  socket.join("some room");
});
```

You can leave a room by using the leave method. Example:

    ```
    io.on("connection", (socket) => {
      socket.leave("some room");
    });
    ```

# Namespaces

A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

Each namespace potentially has its own what? (hint: 3 things)
The three things that each namespace potentially has its own are:

- Main namespace
- Custom namespaces
- Dynamic namespaces

  A possible use case for separate namespaces is when you want to have a different set of functionality for different users. For example, you could have a namespace for users and a namespace for admins. The users namespace would have the functionality for users and the admin namespace would have the functionality for admins. This would allow you to have different functionality for different users.

# Reflection

My goals after reading and reviewing the class README are understanding the following:

- Messaging Queues by Ordered (FIFO) and Unordered
- Socket.io Chat Example
- Routing events and messaging between clients and servers
- Implementing a Queue Server

### Resources I use

hat Example[^1], Rooms[^2], and Namespaces[^3]

[^1]: [Socket.io](https://socket.io/get-started/chat/)
[^2]: [Rooms](https://socket.io/docs/v4/rooms)
[^3]: [Namespaces](https://socket.io/docs/v4/namespaces/)
