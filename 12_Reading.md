## 401 Reading Notes

## Socket.io

### Review 
1. What is the benefit of transforming data into packets?
- When you transform data into packets devices on a TCP/IP network divide data into smaller pieces. This allows the network to accommodate various bandwidths, allow for multiple routes, and retransmit the pieces of data which are interrupted or lost. [Link](https://kb.iu.edu/d/anyq)

2. UDP is often refereed too as a connectionless protocol. Why is this?
- A connectionless protocol refers to the communication between two network endpoint without a prior engagement. It is an alternative type of data transmission in which a network endpoint send an IT signal automatically. [Link](https://avinetworks.com/glossary/connectionless-protocol/#:~:text=A%20connectionless%20protocol%20refers%20to,receiving%20end's%20device%20is%20ready.)

3. Can a socket server application have multiple socket connections?
- A socket server application can handle multiple clients simultaneously. You can do this with a listening socket fork. 

4. Can a socket connection application be connected to multiple socket servers?
- Yes it can, but it is listening on a single port. 

5. Can an application be both a socket server and a socket connection?
- It is possible to run input and output streams of a socket on the same thread and supporting a single connection. 

### Define
- Observer Pattern: The observer pattern is a software design pattern in which an object, named the subject, maintains a list of dependents which are called observers. This notifies them automatically of any state changes, usually by calling one of their methods. [Link](https://en.wikipedia.org/wiki/Observer_pattern)

- Listener: A listener is used for listening to events in a web container, such as when you create a session or place an attribute in session. [Link](https://stackoverflow.com/questions/4720942/difference-between-filter-and-listener-in-servlet-java-ee#:~:text=Listener-,Servlet%20Listener%20is%20used%20for%20listening%20to%20events%20in%20a,can%20configure%20listener%20in%20web.)

- Event Handler: An event handler is a callback routine that operates asynchronously and handles inputs received into a program events. [Link](https://searchapparchitecture.techtarget.com/definition/event-handler)

- Event Driven Programming: In computer programming, event driven programs are a paradigm in which the flow of a program, is determined by events such as user actions. [Link](https://en.wikipedia.org/wiki/Event-driven_programming)

- Event Loop: An event loop is a programming construct or design pattern that waits for an dispatches events or messages in a program. [Link](https://en.wikipedia.org/wiki/Event_loop#:~:text=In%20computer%20science%2C%20the%20event,or%20messages%20in%20a%20program.)

- Event Queue: An event queue is a repository where events from an application are held prior to being process by a receiving program or system. [Link](https://www.techopedia.com/definition/24963/event-queue#:~:text=An%20event%20queue%20is%20a,of%20an%20enterprise%20messaging%20system.)

- Call Stack: A call stack is a data structure that stores information about the active subroutines of a computer program. [Link](https://en.wikipedia.org/wiki/Call_stack)

- Emit/Raise/Trigger: Emit the event, Raise the Event, and then trigger the event

- Subscribe: A way to arrange or receive something regularly. 

- database: A database stores parsed information that is passed around through a req, and res on a Web Request, Response, Cycle. 

### Preview
1. Which 3 things had you heard about previously and now have better clarity on?
- How events play a key role with the web
- Well levels of complexity are needed to transfer information
- How data can be divided into smaller chunks and sent on multiple pathways

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- Applying these principles
- Learning about how the events take place within a WRRC
- Ensuring a clean state of transfer 

3. What are you most excited about trying to implement or see how it works?
- Just excited to learn

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
- [Read Message Queues](13_Reading.md)
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