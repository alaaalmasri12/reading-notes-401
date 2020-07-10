# Graphs

### A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.

- Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
- Edge - An edge is a connection between two nodes.
- Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
- Degree - The degree of a vertex is the number of edges connected to that vertex.

### Directed vs Undirected Graphs.

#### Undirected Graphs

- An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.

#### Directed Graphs (Digraph)
- A Directed Graph also called a Digraph is a graph where every edge is directed.

#### Acyclic vs Cyclic
In addition to undirected and directed graphs, we also have acyclic and cyclic graphs.

Acyclic Graph
An acyclic graph is a directed graph without cycles.
A cycle is when a node can be traversed through and potentially end up back at itself.

Cyclic Graphs
A Cyclic graph is a graph that has cycles.
A cycle is defined as a path of a positive length that starts and ends at the same vertex.

#### Graph Representation
- Adjacency Matrix
An Adjacency matrix is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix

- Adjacency List
An adjacency list is the most common way to represent graphs. An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected.

#### Weighted Graphs
A weighted graph is a graph with numbers assigned to its edges. These numbers are called weights.

#### Real World Uses of Graphs
Graphs are extremely popular when it comes to it’s uses. Here are just a few examples of graphs in use:
1. GPS and Mapping
2. Driving Directions
3. Social Networks
4. Airline Traffic
5. Netflix uses graphs for suggestions of products
