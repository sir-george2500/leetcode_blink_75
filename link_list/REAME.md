# Linked List Data Structure

A linked list is a linear data structure in which elements are stored in nodes, and each node points to the next node in the sequence. Unlike arrays, linked lists do not require contiguous memory locations, allowing for dynamic memory allocation and efficient insertion and deletion operations.

## Basic Components

### Node
A node in a linked list consists of two parts:

- **Data**: Holds the value or information.
- **Next Pointer**: Points to the next node in the sequence.

### Head
The head is a reference or pointer to the first node in the linked list. If the list is empty, the head is typically set to `None` or `null`.

## Basic Operations and Time Complexity

A linked list supports the following basic operations:

- **Insertion**: Adding a new node to the list.
  - **Insert at Beginning**: O(1)
  - **Insert at End**: O(n) where n is the number of nodes.
  - **Insert at Given Position**: O(n)
- **Deletion**: Removing a node from the list.
  - **Delete at Beginning**: O(1)
  - **Delete at End**: O(n)
  - **Delete at Given Position**: O(n)
- **Traversal**: Visiting each node in the list.
  - Time Complexity: O(n)
- **Search**: Finding a node with a given value.
  - Time Complexity: O(n)

## Types of Linked Lists

### Singly Linked List
In a singly linked list, each node points to the next node in the sequence, forming a unidirectional chain.

### Doubly Linked List
In a doubly linked list, each node has pointers to both the next and the previous nodes, allowing for bidirectional traversal.

### Circular Linked List
In a circular linked list, the last node points back to the first node, forming a closed loop.

## Common Use Cases

Linked lists are employed in various scenarios, including:

- **Dynamic Memory Allocation**: Allocating memory as needed.
- **Implementation of Stacks and Queues**: Utilizing pointers for efficient push, pop, enqueue, and dequeue operations.
- **Undo Functionality**: Storing the state of an application or system for undo operations.
- **Music Player Playlist**: Managing playlists where each song is a node pointing to the next song.
- **Symbol Tables in Compilers**: Representing a symbol table with linked list nodes.

Linked lists provide flexibility and efficient memory usage, making them suitable for applications that involve frequent insertions and deletions.

