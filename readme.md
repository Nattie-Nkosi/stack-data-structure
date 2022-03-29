# STACK IMPLEMENTATION

### push() Pseudocode

- This function should accept a value.
- Create a new node using the value passed to the function.
- If there is no head property on the list, set the head and tail to be the newly created node.
- Otherwise set the next property on the tail to be the new node and set the tail property on the list to be newly created node.
- Increment the length by 1.
- Return the linked list.

### pop() Pseudocode

- If there are no node in the list, return undefined.
- Loop through the list until you reach the tail.
- Set the next property of the 2nd to last node to be null.
- Set the tail to be 2nd to last node.
- Decrement the length of the list by 1.
- Return the value of the node removed.

### print() Pseudocode

- Create an empty array.
- Create a variable to store a current node.
- Iterate through the list while current is true.
- Push current value to an array.
- Update the current value to the next value of the node.
- Show the array.
