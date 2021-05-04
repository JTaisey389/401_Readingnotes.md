## 401 Reading Notes

## Message Queues

### Review
1. What does it mean that web sockets are bidirectional? Why is this useful?
  - Websocket allows for full-duplex bidirectional communication. This enables a server to send real-time updates asynchronously. [Link](https://www.amx.com/en-US/site_elements/benefits-and-applications-of-websockets#:~:text=Whereas%20HTTP%20relies%20on%20a,submit%20a%20request%20each%20time.)

2. Does socket.io use HTTP? Why?
- HTTP is a connection protocol that runs on a socket, so it's the opposite. HTTP relies on socket for it's connection. 

3. What happens when a client emits an event?
- When the client emits an event an event listener fires off and looks for the programmed information to send to the server. 

4. What happens when a server emits an event?
- It depends on wheat the server wants to send, and ultimately will depend on the request sent in by the client. A server could send back a connect, message, disconnect, reconnect, ping, join and leave.

5. What happens if a client “misses” an event?
- This can cause buffering, buffering consumes lots of memory. 

6. How can we mitigate this?
- Reduce the default message buffer size

### Define
- Socket: Socket is real time, bi-directional and event-based communication

- Web Socket: The WebSocket API is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server. [Link](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)

- Socket.io: See socket from above! 
- Client: A desktop computer or workstation that is capable of obtaining information and applications from a server. 
- Server: A computer or a computer program which manages access to a centralised resource or service in a network.

- OSI Model: The Open Source Interconnection Model is a conceptual framework use to describe the function of a network system. [Link](https://www.forcepoint.com/cyber-edu/osi-model#:~:text=The%20OSI%20Model%20(Open%20Systems,between%20different%20products%20and%20software.)

- TCP Model: A TCP model is a concise version of the OSI model which contains four layers. The layers are application, transport, internet and network access layer. 

- TCP: Transmission Control Protocol
- UDP: User Datagram Protocol
- Packets: Blocks of data transmitted across a network

### Preview 
- Which 3 things had you heard about previously and now have better clarity on?
  * TCP, UDP, and What a TCP Model is

- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  * I am excited to see how a user interacts with a TCP
  * How i could set up a UDP
  * Can you intertwine UPD and TCP

- What are you most excited about trying to implement or see how it works?
  * I am looking forward to the OSI model

### Table of Contents
- [Read Express 01](01_Reading.md)
- [Read Express 02](02_Reading.md)
- [Read Express REST API](03_Reading.md)
- [Read Data Modeling](04_Reading.md)
- [Read Linked Lists](05_Reading.md)
- [Read Authentication](06_Reading.md)
- [Read Bearer Authorization](07_Reading.md)
- [Read Access Control (ACL)](08_Reading.md)
- [Read Express 01](09_Reading.md)
- [Read Stacks and Queues](10_Reading.md)
- [Read Event Driven Applications](11_Reading.md)
- [Read Socket.io](12_Reading.md)
- [Read Event Driven Architecture](14_Reading.md)
- [Read Trees](15_Reading.md)
- [Read AWS: Cloud Servers](16_Reading.md)
- [Read AWS: S3 and Lambda](17_Reading.md)
- [Read AWS: API, Dynamo and Lambda](18_Reading.md)
- [Read AWS: Events](19_Reading.md)
- [Read Component Based UI](26_Reading.md)
- [Read Props and State](27_Reading.md)
- [Read Component Composition](28_Reading.md)
- [Read Routing](29_Reading.md)
- [Read Hash Tables](30_Reading.md)
- [Read Hooks API](31_Reading.md)
- [Read Custom Hooks](32_Reading.md)
- [Read Context API](33_Reading.md)
- [Read Reading: <Login /> and <Auth />](34_Reading.md)
- [Read Retrospective](35_Reading.md)
- [Read Application State with Redux](36_Reading.md)
- [Read Redux - Combined Reducers](37_Reading.md)
- [Read Redux - Asynchronous Actions](38_Reading.md)
- [Read Redux - Additional Topics](39_Reading.md)
- [Read React Native](41_Reading.md)
- [Read Ethics](42_Reading.md)

## Link to Code 102
- [Code 102 Reading Notes](https://jtaisey389.github.io/reading-notes/)

## Link to Code 201
- [Reading Notes 201](https://jtaisey389.github.io/reading-notes201.md/)

## Link to Code 301
- [Reading Notes 301](jtaisey389.github.io/reading-notes301.md/)

[<== Back_to_reading_notes](jtaisey389.github.io/401_readingnotes.md/)