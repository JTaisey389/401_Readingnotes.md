## 401 Reading Notes

## Readings: Redux - Additional Topics

### Review

1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application? The asynchronous action within the lifecycle method would need to be fired off. In this situation you would not use the results of the API call that is directly mounted to the component. A thunk middleware would be called in to handle the asynchronous action and from there you call mapStateToProps. [Link](https://www.reddit.com/r/reactjs/comments/fvgxh4/best_practice_for_loading_data_in_redux_store_on/)

2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer? You would dispatch your application with a creator.

### Define

- middleware: Middleware is a software that provides services and capabilities to applications outside of what is offered by the operating system.

- thunk: Thunk is a way you have an action do something that needs code to live inside of a function.

### Preview 

1. Which 3 things had you heard about previously and now have better clarity on?

- Middleware
- Most of the other items are new to me

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

- Pre-loading data within react state
- How to add thunk to a function
- How middleware will be implemented into React

3. What are you most excited about trying to implement or see how it works?

- I am looking forward to adding middleware 

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
- [Read React Native](41_Reading.md)
- [Read Ethics](42_Reading.md)

## Link to Code 102

- [Code 102 Reading Notes](https://jtaisey389.github.io/reading-notes/)

## Link to Code 201

- [Reading Notes 201](https://jtaisey389.github.io/reading-notes201.md/)

## Link to Code 301

- [Reading Notes 301](jtaisey389.github.io/reading-notes301.md/)

[<== Back_to_reading_notes](jtaisey389.github.io/401_readingnotes.md/)
