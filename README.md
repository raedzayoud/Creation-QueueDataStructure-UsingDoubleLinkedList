
## clsMyQueue: Library C++ Queue Implementation

clsMyQueue is a C++ template class that implements a queue data structure using a double linked list for efficient FIFO (First-In-First-Out) operations. It offers a comprehensive set of features for various queue-based applications.

Key Features:

Efficient FIFO Operations (O(1) average complexity):

<strong>push(Item)</strong>: Enqueues an item to the back of the queue.

<strong>pop()</strong>: Dequeues an item from the front of the queue.

<strong>front()</strong>: Returns the first item without removing it.

<strong>back()</strong>: Returns the last item without removing it.

<strong>GetItem(Index)</strong>: Retrieves an item at a specified index.

<strong>Size()</strong>: Returns the current number of items in the queue.

<strong>IsEmpty()</strong>: Checks if the queue is empty.

Advanced Functionality:

<strong>Reverse()</strong>: Reverses the order of elements in the queue.

<strong>UpdateItem(Index, NewValue)</strong>: Updates the value of an existing item.

<strong>InsertAfter(Index, NewValue)</strong>: Inserts a new item after a specified index.

<strong>InsertAtFront(Value)</strong>: Inserts an item at the front of the queue.

<strong>InsertAtBack(Value)</strong>: Inserts an item at the back of the queue (equivalent to push).

<strong>Clear()</strong>: Removes all items from the queue.
Template-Based Design: Supports queues of various data types for flexibility.
