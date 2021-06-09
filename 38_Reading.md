## 401 Reading Notes

## Readings: Redux - Asynchronous Actions

### Review

1. How granular should your reducers be? : At the whole reducer functions should only depend on their state and action arguments.

2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched: I think this would depend on the scenario, there may be times when you need multiple dispatch events for a function call to work.

3. Name a strategy for preventing the above: I think an approach would be to make sure that you don't have a set of dispatch events relying on a singular component. Each component ideally needs its own reducer.

### Define

- store: A store is an immutable object tree in Redux.
- combined reducers: The combined reducers function turns an object whose values are different reducing functions into a single reducing function that you can pass.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?

- What a reducer is
- How to combine a reducer
- What amount of detail should your reducer be

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

- More about combined reducers
- How to keep reducers not overloaded with data
- What is the best way to manage reducers

3. What are you most excited about trying to implement or see how it works?

- Using reducers

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
