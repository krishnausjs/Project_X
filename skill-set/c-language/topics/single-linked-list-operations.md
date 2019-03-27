# About Linked lists

## Introduction
- Linked list is a linear collection of data elements (called nodes).
- In its most basic form, each node contains: data, and a reference (in other words, a link) to the next node in the sequence.
- Single linked list node is represented as

```
struct Node
{
  int data;
  struct Node *next;
};
```

## Advantages of linked lists
- Linked list structure allows for efficient insertion or removal of elements from any position in the sequence during iteration. More complex variants add additional links, allowing more efficient insertion or removal of nodes at arbitrary positions.

- Linked lists are among the simplest and most common data structures. They can be used to implement several other common abstract data types, including lists, stacks, queues, associative arrays, and S-expressions.

- Linked list are dynamic, so the length of list can increase or decrease as necessary. Each node does not necessarily follow the previous one physically in the memory.

## Disadvantages of Linked Lists
- A drawback of linked lists is that access time is linear (and difficult to pipeline). Faster access, such as random access, is not feasible. Arrays have better cache locality compared to linked lists.

- They use more memory than arrays because of the storage used by their pointers.

- Nodes in a linked list must be read in order from the beginning as linked lists are inherently sequential access.

- Nodes are not stored continuously , greatly increasing the time periods required to access individual elements within the list, especially with a CPU cache.

- Difficulties arise in linked lists when it comes to reverse traversing. For instance, singly linked lists are cumbersome to navigate backwards[1] and while doubly linked lists are somewhat easier to read, memory is consumed in allocating space for a back-pointer.

## Linked Lists Vs arrays
- The principal benefit of a linked list over a conventional array is that the list elements can be easily inserted or removed without reallocation or reorganization of the entire structure because the data items need not be stored contiguously in memory or on disk, while restructuring an array at run-time is a much more expensive operation.

- Linked lists allow insertion and removal of nodes at any point in the list, and allow doing so with a constant number of operations by keeping the link previous to the link being added or removed in memory during list traversal.


Source : [Linked_list](https://en.wikipedia.org/wiki/Linked_list).
