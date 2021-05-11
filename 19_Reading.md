## 401 Reading Notes

## Readings: AWS: Events

### Review:

1. Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server: Both interact with API's but have different approaches to how the interact with API's. They all interact with a server in some way or form and rely on the function of each-other to perform an action. 

2. List the AWS Database offerings and talk about the pros and cons of each: [Link](https://www.trustradius.com/products/amazon-relational-database-service/reviews?qs=pros-and-cons)

- Efficient
- Scalable
- Cost Reduction
- No root access to servers
- Downtime is required
- Not a zero Administration database

3. What’s the difference between a FIFO and a standard queue?: Standard queues provide at-least-once delivery, which means that each message is delivered once. A FIFO queue provides exactly-one processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.
[Link](https://aws.amazon.com/sqs/faqs/#:~:text=Standard%20queues%20provide%20at%2Dleast,processes%20it%20and%20deletes%20it.)

4. How can the server be assured a message was properly received?: When a request is sent to the server the server can respond back and emit an event that sends data back to the user to show that information is being processed.

### Define

- Server-less API: It is cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. An application such as this runs stateless to compute containers that are event-triggered. [Link](https://hackernoon.com/what-is-serverless-architecture-what-are-its-pros-and-cons-cc4b804022e9)

- Triggers: In general a trigger generally causes a program routine to be executed.

- Dynamo vs Mongo: Dynamo is a fully manages AWS service, MongoDB can be self installed. Dynamo uses tables, items and attributes, MongoDB uses JSON-like documents. [Link](https://www.xplenty.com/blog/dynamodb-vs-mongodb-differences/#:~:text=DynamoDB%20is%20a%20fully%20managed,fully%20managed%20with%20MongoDB%20Atlas.&text=DynamoDB%20uses%20tables%2C%20items%20and,and%20has%20fewer%20size%20restrictions.)

- Dynamoose vs Mongoose: Dynamoose is a modeling tool for Amazon's DynamoDB which is inspired after Mongoose. [Link](https://www.npmjs.com/package/dynamoose)

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?

- FIFO: First in first out
- How a messaging queue works
- How best to ensure a client receives a message.

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

- How much Amazon has manipulated it's architecture to be modeled after successful database software
- Is there a best way to ensure data centers process information efficiently
- In some shape or form do most servers implement a queue based on the REQ, RES cycle

3. What are you most excited about trying to implement or see how it works?

- Learning about how Amazon has emulated many types of cloud servers and databases.

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
- [Read Message Queues](13_Reading.md)
- [Read Event Driven Architecture](14_Reading.md)
- [Read Trees](15_Reading.md)
- [Read AWS: Cloud Servers](16_Reading.md)
- [Read AWS: S3 and Lambda](17_Reading.md)
- [Read AWS: API, Dynamo and Lambda](18_Reading.md)
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