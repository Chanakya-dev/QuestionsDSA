# Basic Linked List Operations

## 1. Insertion
### a. At the Beginning
- **Description**: Add a new item to the start of the linked list.
- **Steps**:
  1. Create a new node with the desired value.
  2. Set the new node's next pointer to the current head of the list.
  3. Update the head of the list to point to the new node.

### b. At the End
- **Description**: Add a new item to the end of the linked list.
- **Steps**:
  1. Create a new node with the desired value.
  2. If the list is empty, set the head to the new node.
  3. Otherwise, traverse the list to find the last node.
  4. Set the last node's next pointer to the new node.

### c. At a Given Position
- **Description**: Insert a new item at a specific position in the linked list.
- **Steps**:
  1. Create a new node with the desired value.
  2. Traverse to the node just before the desired position.
  3. Adjust pointers to include the new node in the list.

## 2. Deletion
### a. From the Beginning
- **Description**: Remove the item at the start of the linked list.
- **Steps**:
  1. Update the head of the list to point to the second node.

### b. From the End
- **Description**: Remove the item at the end of the linked list.
- **Steps**:
  1. Traverse the list to find the second-to-last node.
  2. Set its next pointer to null.

### c. From a Given Position
- **Description**: Remove an item from a specific position in the linked list.
- **Steps**:
  1. Traverse to the node just before the desired position.
  2. Adjust pointers to skip the node to be deleted.

## 3. Traversal
- **Description**: Access and print each item in the linked list.
- **Steps**:
  1. Start from the head.
  2. Follow the next pointers to visit each node until the end.

## 4. Searching
- **Description**: Find an item in the linked list.
- **Steps**:
  1. Start from the head.
  2. Compare each node's value with the target value until found or the end is reached.

## 5. Finding the Length
- **Description**: Calculate the number of items in the linked list.
- **Steps**:
  1. Initialize a counter to zero.
  2. Traverse the list, incrementing the counter for each node.

## 6. Displaying the List
- **Description**: Print the contents of the linked list.
- **Steps**:
  1. Start from the head.
  2. Traverse the list, printing the value of each node.

## Summary
These basic operations provide an understanding of how linked lists function without delving into complex algorithms or data structures.
