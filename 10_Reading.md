## 401 Reading Notes

## Stacks and Queues

### What is a Stack?
- A stack is a data structure that consists of **Nodes** and each **Node** references the next **Node** in the stack, but will not reference the previous.

- Common terms for a stack
1. Push - Nodes or items that are put into the stack that are pushed
2. Pop - Nodes or items that are removed from the stack are popped. When you attempt to **pop** an empty stack an exception will be raised.
3. Top - This refers to the top of the stack
4. Peek - When you **peek** you will view the value of the **top** node in the stack. When you attempt to **peek** an empty stack an exception will be raised. 
5. IsEmpty - This returns true when stack is empty otherwise it returns false

### Stack terms
- Array.pop 

- The pop() method removes the last element of an array, and returns that element.
  * Note: This method changes the length of an array.
  * Tip: To remove the first element of an array, use the shift() method.

https://www.w3schools.com/jsref/jsref_pop.asp

- The time for these are 0(n) - > O of one
- Space for the pop method 0(n) - > O of one
- Stacks follow these concepts:
  * FILO - **F**irst **I**n **L**ast **O**ut
  * This means the first item added in the stack will be the last item popped out of the stack

  * LIFO - **L**ast **I**n **F**irst **O**ut
  * This means that the last item added to the stack will be the first item popped out of the stack

## Stack Visualisation
![Stack](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/stack1.PNG)
![Pop](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/pushStack2.PNG)
![Finish](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/pushStack3.PNG)

### Queueing 
- Common terms for a queue
1. Enqueue - Node or items that are added to the queue
2. Dequeue - Node or items that are removed from the queue. If called when the queue is empty an exception will be raised
3. Front - This is the front/first node of the queue
4. Rear - This is the rear/last node of the queue
5. Peek - When you peek you will view the value of the from node in the queue
6. IsEmpty - Returns true when queue is empty but otherwise returns false

### Refrences
[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)


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