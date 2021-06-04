## 401 Reading Notes

## Readings: Graphs

- Graphs area non-linear data structure that can be looked at as a collection of vertices  or nodes which are potentially connected to segments named edges.

## Common Terms

- Vertex: A vertex, also called a "node", is a data object that can have zero or more adjacent vertices.
- Edge: An edge is a connection between two nodes
- Neighbor: The neighbors of a node are its adjacent nodes and are connected by an edge
- Degree: The degree of a vertex is the number of edges connected to a vertex.

## Directed/Undirected

- A **undirected graph** is a a type of graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in a specific direction.

- In this example the graph below, Node *C* is connected to Node *A*, *E* and node *B*. There are no directions given to specific vertices, this type of connection is bi-directional.

[Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

![Example](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/UndirectedGraph.PNG)

**Directed Graphs**

- A directed graph or Digraph is a graph where every edge is directed. Unlike a undirected graph, a Digraph has a direction. Here is an example of a digraph.

[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/DirectedGraph.PNG)

**Complete vs Connected vs Disconnected**

- Complete graph is when all the nodes are connected to all other nodes.

[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/CompleteGraph.PNG)

- Connected graph is a graph that has all of its vertices/nodes have a least one edge.

[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/ConnectedGraph.PNG)

- Disconnected graph is a graph where some vertices may not have edges

[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/DisconnectedGraph.PNG)

### Acyclic/Cyclic

- In addition to undirected and directed graphs, there are acyclic and cyclic graphs.

**Acyclic**

- A acyclic graph is a directed graph without cycles, a cycle is when a node can be traversed through and potentially end up back at itself. 

[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/threeAcyclic.png)

**Cyclic**

- A cyclic graph is a graph that has cycles. A cycle is a defined path of a positive length that starts and ends at the same vertex.

[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/cyclic.PNG)

### Adjacency Matrix/Adjacent List

**Adjacency Matrix**

- Adjacency Matrix is represented through a 2-dimensional array. 

[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/AdjMatrix.PNG)

**Adjacency List**

- Adjacency list is the most common way to represent a graph. It is a collection of lists or arrays that list all of the other vertices that are connected. 

[Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/AdjList.PNG)


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