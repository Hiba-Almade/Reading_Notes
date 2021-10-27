## Trees


* Node: A tree node is a component that contains values, and references to other nodes
* Root: The root is the node at the beginning of the tree
* K : The maximum number of children a node can have in a tree.
* Left: A reference to one child node, on the left side
* Right : a reference to another child node, on the right side
* Leaf: tree that has no children
* Height: is the number of edges from the root to the farthest leaf.

----

## Traversal: search for a node, and print the contents of the tree.

#### Two categories of scans:

1. Depth First :

`>>` 3 ways to depth first:

pre-order: `root >> left >> right`

in order: `left >> root >> right`

later order:`left >> right >> root`

2. breadth first:

iterates through the tree by going through each node level of the tree one by one

---


### Binary tree vs K-ary trees
#### Binary trees:

limit the number of children to two, there is no specified sort order, and nodes can be added in a binary tree wherever space permits

### K-ary Trees:

nodes that can have more than two children. K indicates the maximum number of children each node can have


> The time complexity of insertions and searches in a binary search tree is O(n).