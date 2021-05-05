## 401 Reading Notes

## Trees

- Today we will discuss trees and this will cover **Binary Trees**, **Binary Search Trees**, and **k-ary Trees**.

### Common Terminology

- Node - A tree node is component which may contain it's own values, and references to other nodes
- Root - The root is the node at the beginning of the tree
- K - A number that specifies the maximum number of children any node may have in a k-ary tree.
- Left - A reference to one child node, in binary tree
- Right - A reference to the other child node, in a binary tree
- Edge - The edge in a tree is the link between a parent and a child node
- Leaf - A leaf is a node that does not have any children
- Height - The height of a tree is the number of edges from the root to the furthest leaf

[Trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

### Sample Tree

![Tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree1.PNG)

### Traversals

- An important aspect of trees is how to traverse them. Traversing a tree allows us to search for a node, print out the contents of a tree, and much more. There are two categories of traversals when it comes to trees:
  - Depth First
  - Breadth First

### Depth First

- Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we print the root
  - Pre-Order: ***root >> left >> right***
  - In-Order: ***left >> roof >> right***
  - Post-Order: ***left >> right >> root***

![Example](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/tree-example.png)

### Breadth First

- Breadth first traversal iterates through the tree by going through each level of the tree node by-node.

![Example](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BreadthTraversal2.PNG)

- Our output using breadth first traversal is now:
  - Output: A, B, C, D, E, F

  - - Traditionally, breadth first traversal uses a queue (instead of the call stack via recursion) to traverse the width/breadth of the tree. Let’s break down the process.

Given our starting tree shown above, let’s start by putting the root into the queue:

### Binary Tree Vs K-ary Trees

- In all of our examples, we have used a binary tree. Trees can have any number of children per node, but binary trees restrict the number of children to two.

![Binary Tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree2.PNG)

### K-ary Trees

- If nodes are able to have more than two child nodes, we call the tree that contains them a K-ary tree.

- Traversing a K-ary tree requires a similar approach to the breadth first traversal

![Example](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/KaryTree1.png)


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
