## 401 Reading Notes

## Event Driven Applications
- Event driven programming is a the logical pattern that we can choose to confine out programming within to avoid issues of complexity and collision. Each time you interact with a webpage through its users interface an event takes place. 

- Event driven programming makes use of the following concepts 
  * An event handler which is used as a callback function that will be called when an event is triggered
  * A main loop which is listening for those events to trigger and routes the calls associated event handler for the event

- An example would be a login in screen for a computer, for example the user has Admin control access. Based off of the store values within a database the event listener will route based on the inputs of the user. For this circumstance the event listener fires off for the Authorisation route to verify the information, then it will trigger a handle event to authenticate the information. 

### Review
1. Why is access control important? - Access control is important because you are routing users based off of their logins. If the users login happens to specify that they are an Admin, that means they have capacity to C.R.U.D (Create, Read, Update, Delete). This is important because you don't want a reader to accidentally deleting a database or messing with a route for purchasing merchandise.

2. Describe an application that would need access control. - An application that would need access control would be a server, a server has extremely valuable information stored on it. 

3. What is a role used for? - A role assigns a value to the property of that user, this will establish at what level a users role can traverse within a system.
4. Why is role based access control more scalable than discretionary or mandatory access control?

### Define
- Authorisation: A token or artefact that is an action to provide authorisation or to authenticate a users credentials. 

- Role based access control: Role based access control is a method for which assigns users values based on their roles. These assigned values determine at what level a user can traverse a file structure within a system.

- Capabilities: In a similar fashion to role based access control, a users capabilities allowed them to perform certain actions within a system. 

### Preview 
1. Which 3 things had you heard about previously and now have better clarity on?
- Event listeners look for what type of access a user has and triggers based off of that
- A users credentials have specific routes depending on the level of access
- Event listeners are similar to middleware because they happen in the middle of a transaction.

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- How these event listeners respond to bad requests
- If the event listeners would have their own feedback loop as to not trigger a sever call
- If a users filled out a form is there a need for a click even to take place for the information to be sent.

3. What are you most excited about trying to implement or see how it works?
- I am looking forward to seeing how best to implement the event listeners within the routes of our files

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