# Stack Implementation using LinkedList in JavaScript

This project presents a Stack data structure implemented using a LinkedList in JavaScript. The code includes classes for `Node`, `LinkedList`, and `Stack`.

## Node Class

The `Node` class represents individual nodes in the linked list. Each node contains:

- `data`: Holds the value of the node.
- `next`: Points to the next node in the list.

### Methods

- `setNextNode(node)`: Sets the reference to the next node.
- `setNext(data)`: Sets the reference to the next node using data directly.
- `getNextNode()`: Retrieves the reference to the next node.

## LinkedList Class

The `LinkedList` class manages the linked list, maintaining a reference to the head node.

### Methods

- `addToHead(value)`: Adds a new node containing the given value to the beginning of the list.
- `addToTail(value)`: Adds a new node containing the given value to the end of the list.
- `findNodeIteratively(comparator)`: Searches for a node in the list based on the provided comparator function.
- `removeHead()`: Removes the head node from the list.
- `size`: Getter property that returns the size of the linked list.

## Stack Class

The `Stack` class is built on top of the `LinkedList` class to implement a stack data structure.

### Methods

- `hasRoom()`: Checks if the stack has room for more elements.
- `isEmpty()`: Checks if the stack is empty.
- `push(value)`: Adds an element to the top of the stack.
- `pop()`: Removes and returns the element from the top of the stack.
- `peek()`: Retrieves the element from the top of the stack without removing it.

