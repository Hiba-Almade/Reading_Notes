## Graphs:
* **Graph** - a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.
    - **Vertex** - also called a “node”, is a data object that can have zero or more adjacent vertices.
    -  **Edge** -  a connection between two nodes.
    - **Neighbor** - neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
---
#### Undirected Graph :
is a graph where each edge is undirected or bi-directional, and this means that the undirected graph does not move in any direction.
#### Directed Graph:
also called a Digraph is a graph where every edge is directed. Each node is directed at another node with a specific requirement of what node should be referenced next.
#### Complete graph:
is when all nodes are connected to all other nodes.
#### Connected graph:
is graph that has all of vertices/nodes have at least one edge. A Tree is a form of a connected graph.
#### Disconnected graph:
is a graph where some vertices may not have edges.
#### Acyclic graph :
is a directed graph without cycles. Cycle is when a node can be traversed through and potentially end up back at itself.
#### Cyclic graph:
is a graph that has cycles. Cycle is defined as a path of a positive length that starts and ends at the same vertex.

---
### Adjacency matrix:

is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix
* Sparse graph - is when there are very few connections
* Dense graph - is when there are many connections
* Adjacency list is the most common way to represent graphs, and is a collection of linked lists or array that lists all of the other vertices that are connected. Also, make it easy to view if one vertices connects to another.
* Weighted graph - is a graph with numbers assigned to its edges. These numbers are called weights.

---
#### Traversals :
required to traverse through a graph. The traversals itself are like those of trees.

`>>` Breadth first traversal start at a specific vertex/node. This node must be specified when calling the BreadthFirst() method.
- Enqueue the declared start node into the Queue.
- Create a loop that will run while the node still has nodes present.
- Dequeue the first node from the queue.
- If the Dequeue‘d node has unvisited child nodes, add the unvisited children to visited set and insert them into the queue.

`>>` Depth first traversal, we approach it a bit different than the way we do when working with a depth first traversal of a tree. Similar to how the breadth-first uses a queue, we are going to use a Stack for our depth-first traversal.


* Real World Uses of Graphs:
    - GPS and Mapping
    - Driving Directions
    - Social Networks
    - Airline Traffic
    - Netflix uses graphs for suggestions of products