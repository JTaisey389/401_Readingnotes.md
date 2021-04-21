## 401 Reading Notes

### Linked Lists
- Linked list is a sequence of **Nodes** that are connected/linked to each other. The defining feature of a linked list is tat **Node** references the next **Node** in the link. 

- There are two types of Linked list - Singly and Doubly
  * Singly: Singly refers to the number of references the node has. A **singly** linked list means that there is only one reference, and the reference points to the **next** node.

  * Doubly: Doubly refers to there being two (double) references within the node. A **doubly** linked list means that there is a reference to both the **next** and additionally the **previous** node.

- ![What it looks like](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/images/LinkedList1.PNG) 

### Traversing
- As you traverse a linked list, you cannot use a **forEach** or a **for** loop. We are relying on the **Next** value to guide the node to the next reference point. A **next** property is exceptionally important because it will lead us to the next node and allows us to extract data appropriately.

- So what can you use to traverse?? The best approach is to use a **while()** loop. This will allow us to continually check that the **next** node is the list is not null. 

**Example**

ALGORITHM Includes (value)
// INPUT <-- integer value
// OUTPUT <-- boolean

  Current <-- Head

  WHILE Current is not NULL
    IF Current.Value is equal to value
      return TRUE

    Current <-- Current.Next

  return FALSE

### What took place

1. We first create **Current** at the **Head** to guarantee we are starting from the beginning.
2. We create the **while** loop and this will only run is the node that **Current** is pointing too is not null.
3. Once we are in the while loop, we are checking if the value of the current node is equal to the value that we were looking for.
4. If the **Current** node does not contain the value we are looking for, we must move the current to the next node that is being referenced.
5. At this point, the while loop is run again and steps 3 & 4 will continue until **Current** reaches the end of the **LinkedList**.

### Adding a Node
 - Order of operations is extremely important when it comes to working with a Linked list. Each of your links and nodes should be properly assigned. 

### Prerequisites
- When constructing your code, keep in mind that a Node class will be passed in to each node that has a value.

[Linked List Reading](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)


### Table of Contents
- [Read Express 01](01_Reading.md)
- [Read Express 02](02_Reading.md)
- [Read Express REST API](03_Reading.md)
- [Read Data Modeling](04_Reading.md)
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