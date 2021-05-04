## 401 Reading Notes

## Event Driven Architecture

### Review
1. What’s the difference between a FIFO and a standard queue?: FIFO queues have essentially the same features as a standard queue, but provide an additional benefit of supporting ordering and exactly-once processing. [Link](https://aws.amazon.com/about-aws/whats-new/2016/11/amazon-sqs-introduces-fifo-queues-with-exactly-once-processing-and-lower-prices-for-standard-queues/#:~:text=FIFO%20queues%20have%20essentially%20the,being%20received%20by%20message%20consumers.)

2. How can the server be assured a message was properly received?: A server could be configured in a way that when a message is sent, a response is expected back. This would ensure that the message is received, the alternative is to program in a set of responses on the client end. 

3. What classic design pattern is best represented by event driven programming?: An observer pattern is a software design pattern in which an object, named the subject, maintains a list of dependencies. called observers. [Link](https://en.wikipedia.org/wiki/Observer_pattern)

4. How do you test an event driven system?: With most cases you write a unit test, service test, and a end-to-end test. These are known as **System Under Test** (SUT) [Link](https://medium.com/dan-on-coding/testing-event-driven-systems-63c6b0c57517)

### Define
- FIFO Queue: These are queues designed to enhance messaging between applications when the order of operations and events are critical, or where duplicates can't be tolerated. [Link](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/FIFO-queues.html)

- Pub/Sub: Pub/sub is an asynchronous messaging service that decouples services that produce events from services that process events. [Link](https://cloud.google.com/pubsub/docs/overview)

### Preview 
1. Which 3 things had you heard about previously and now have better clarity on?
- Our reading today was all new material I have not heard of, but a lot of the sources come from either google or amazon. 
- I did learn about the FIFO system the other day, and it makes sense that chat queues are designed that way. 
- I asked myself the question about the FIFO method and how that is related to the systems we are learning with event.emits. 

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- Looking forward to tying in the event based events to trigger FIFO's.
- I would like to implement or learn more about the setting up of the architecture on these systems
- Is there a way that an event could be disabled that does not disrupt the event.emit process?

3. What are you most excited about trying to implement or see how it works?
- It will be interesting to see how chat queue's are developed. 

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