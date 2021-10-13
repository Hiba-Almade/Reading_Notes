# Linked Lists:


## What is a linked list?

A linked list is a series of nodes that are connected to each other as each node points to the next node in the link.

`>>` Two types of linked lists: single and double:

* **Single:** A singly linked list means that there is only one reference, and the reference points to the next node in a linked list.
![singly](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist_insert_last.png)

* **Doubly :**  Adoubly indicates that there are two references within a node, for both the next and the previous node.

![doubly](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2014/03/DLL1.png)

`>>` We also have:

* **node :**

 Nodes are the elements.

* **Next :**

This property contains a reference to the next node.

* **Head :**
 The header is a reference to the first node in a linked list.
current - current is a reference to the node that is currently being looked at.

--------


`>>` A linked list is usually efficient when it comes to adding and removing most items, but it can be very slow to search and find a single item.


`>>` The difference between arrays and linked lists is the way they use memory in our machines.

When an array is created, it needs a certain amount of memory in one place.

But when you create a linked list, it doesn't need units of memory all in one place. One byte can live somewhere, while the next byte can be stored somewhere else in memory altogether!

