## 401 Reading Notes

## Readings: Hooks API

### Review

1. Why do we not need more .html pages in a multi-page React app?: With React you can set the frameworks up in such a way that you only need one central HTML page which compiles all the resources onto the page.

2. If we wanted a component to show up on every page, where would we put it and why?

- Outside the <BrowserRouter/>: This is set up for regular URL paths so you could set up a function or a class to have the specific item show up within each page, and example of that would be a footer. 

- Inside the <BrowserRouter />, outside a <Route />: If you want a component set up within the Browser router you could set it up to where the component is returned within the Browser router and export that to other areas. 

- Inside a <Route />: Within a similar concept of returning the component within Browser router. The major difference is that because your at a specific export you would have to pass the state out of the route to a component level.

3. What does props.children contain?: It is used to display whatever you include between the opening and closing tag when invoking a function.

### Define

- Composition: Composition in a way is an approach to contain specific elements within your frameworks.
- Children / Child Components: An example of children/child components would be an unordered list. A UL is a parent element and within the parent elements are the list items which are the children.

- Hash Routing: Hash routing uses an anchor part of the URL to simulate different content. 
- Link Routing: The concept is that every node constructs a map of the connectivity to the network, in the form of a graph, showing which nodes are connected to which other nodes.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?

- What a hash's purpose is with React
- How children are components of a parent
- How link routing is like a chain 

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

- Hash Routing
- Link Routing
- How to best set up composition

3. What are you most excited about trying to implement or see how it works?

- I am looking forward to the deep dive into React and implementing Hash routing

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
