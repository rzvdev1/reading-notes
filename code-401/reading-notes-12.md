# Socket.io

# Web Sockets

WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The Web Socket request/response handshake is a HTTP request that is sent to the server. Once the connection is established, the client and server can send messages to each other at any time. Web Sockets provide a standardized way for the server to send content to a client without first receiving a request from that client.

# Socket.io Tutorial

The event handler io.on() is used to handle the connection event for incoming sockets. The possible proof of life is the console.log() that is used to log the message to the console and also use setTimeout() to emit a new event to the client after a couple of seconds. The socket.emit() emits a message to the client that is connected

# Socket.io vs Web Sockets

The difference between WebSocket and Socket.IO is that WebSocket is a communication protocol that provides a full-duplex communication channel over a single TCP connection established between a web browser and a web server while Socket.IO is a library for WebSockets that makes it easier to use WebSocket by providing extra features. You would use Socket.IO when you want to use WebSockets but you want to support older browsers that don't natively support WebSockets. Socket.IO also provides a fallback mechanism that allows you to use other techniques if WebSockets are not available. You would use WebSockets when you want to establish a full-duplex communication channel between a web browser and a web server. This is useful for applications that require makes real-time communication effortless and efficient .

# OSI Model Explained

The key takeaways from this video are the following:

- The OSI model is a conceptual model that characterizes and standardizes the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.
- They have seven layers, each of which provides services to the layer above it and receives services from the layer below it.
- The seven layers of the OSI model are the application layer, presentation layer, session layer, transport layer, network layer, data link layer and physical layer.
- The application layer is the OSI layer closest to the end user, which means both the OSI application layer and the user interact directly with the software application.
- The presentation layer establishes context between application-layer entities, in which the application-layer entities may use different syntax and semantics if the presentation service provides a mapping between them.
- The session layer controls the dialogues (connections) between computers.
- The transport layer provides transparent transfer of data between end users, providing reliable data transfer services to the upper layers.
- The network layer provides the functional and procedural means of transferring variable length data sequences (called packets) from one node to another connected in "different networks".
- The data link layer provides the functional and procedural means to transfer data between network entities and to detect and possibly correct errors that may occur in the physical layer.
- The physical layer defines the electrical, mechanical, procedural, and functional specifications for activating, maintaining, and deactivating the physical link between communicating network systems.

# TCP Handshakes Explained

Translate the gist of this video to a non-technical friend
The TCP handshake is a three-way process that establishes a socket connection between two computers. They talk to each other and agree on the parameters of the connection before starting to communicate. The three steps are SYN, SYN-ACK, and ACK. The first step is the client sends a SYN packet to the server. The second step is the server responds with a SYN-ACK packet. The third step is the client responds with an ACK packet. The TCP handshake is a three-way process that establishes a socket connection between two computers. They talk to each other and agree on the parameters of the connection before starting to communicate. The three steps are SYN, SYN-ACK, and ACK. The first step is the client sends a SYN packet to the server meaning can you open the server connection. The second step is the server responds with a SYN-ACK packet mean the server acknowledge the request and ask client to open a connection too. The third step is the client responds with an ACK packet meaning yes.

## Reflection

My goals after reading and reviewing the class README are understanding the following:

- Implement a standalone Socket.io server for handling events and real time messaging.
- Use events to properly route incoming messages and payload
- Internet Protocol Suite is described using four layers - Link, Internet, Transport, and Application
- Web Sockets
- Socket.io Library
- OSI Model
- TCP Handshakes

### Resources I use

WebSocket[^1], Socket.io[^2], Socket.io vs Web Sockets[^3] OSI Model[^4], and TCP Handshakes[^5]

[^1]: [WebSocket](https://en.wikipedia.org/wiki/WebSocket)
[^2]: [Socket.io](https://www.tutorialspoint.com/socket.io/)
[^3]: [WebSocket](https://www.educba.com/websocket-vs-socket-io/)
[^4]: [OSI Model](https://www.educba.com/websocket-vs-socket-io/)
[^5]: [TCP](https://www.youtube.com/watch?v=xMtP5ZB3wSk)
