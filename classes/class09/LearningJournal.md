# Learning Journal

## I have learned Implementing a Stack using a Linked List:
1. Define a class for the Stack.
2. Create a Node class to represent each element in the Stack.
3. Initialize the Stack with an empty head node.
4. Implement the `push` operation:
   - Create a new Node with the given value.
   - Set the next pointer of the new node to the current head.
   - Set the new node as the new head of the Stack.
5. Implement the `pop` operation:
   - Check if the Stack is empty (head is None).
   - If not empty, store the value of the current head.
   - Set the head to the next node.
   - Return the stored value.
6. Implement the `peek` operation:
   - Check if the Stack is empty.
   - If not empty, return the value of the head node.
7. Implement the `isEmpty` operation:
   - Check if the Stack is empty.
   - Return True if the head is None; otherwise, return False.


   
## I  have lernd Implementing a Queue using a Linked List:

1. Define a class for the Queue.
2. Create a Node class to represent each element in the Queue.
3. Initialize the Queue with empty head and tail nodes.
4. Implement the `enqueue` operation:
   - Create a new Node with the given value.
   - If the Queue is empty, set both head and tail to the new node.
   - Otherwise, set the next pointer of the current tail to the new node.
   - Set the new node as the new tail of the Queue.
5. Implement the `dequeue` operation:
   - Check if the Queue is empty (head is None).
   - If not empty, store the value of the current head.
   - Set the head to the next node.
   - If the head becomes None, set the tail to None as well.
   - Return the stored value.
6. Implement the `peek` operation:
   - Check if the Queue is empty.
   - If not empty, return the value of the head node.
7. Implement the `isEmpty` operation:
   - Check if the Queue is empty.
   - Return True if both head and tail are None; otherwise, return False.

