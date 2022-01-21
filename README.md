# Based on what we know about linked lists, stacks, and queues, design a queue data structure:
## ▼ What functions are we likely to need for a queue?
### ADD function
Add a value to a queue after a previously added value.
### REMOVE function
Remove a lastly added value from a queue.
### IS EMPTY function
Check if a queue is empty. Notice availability of the Remove function.
### IS FULL function
Check if a queue is full of values. Notice availability of the Add function.

## ▼ What values will we need to know about the structure for our queue to function properly?
### Tail
A location number where a new value is added.
### Head
A location number where a value that is subject to removing.
### Length
A number of values a queue can store.<br>
If a Tail reaches the Length and a queue storage is available, Tail is back to 0.


# Based on what we know about linked lists, design a list data structure that allows us to add (insert) or remove (delete) values at a given location in the list (instead of the top of a stack or the front or back of a queue):
## ▼ What functions are we likely to need for a list to function like this?

### ADD function
Get location info of two list elements (e.g. defined as prev and next), and insert a new element between them using the info.

### REMOVE function
Associate two nodes which are located after and before a subject list element.
Then remove the subject element.

### SEAECH function
Check an existence or a location of a list element based on id number or the elemnt's info.


## ▼ What values will we need to know about the structure for our list to function properly?
### Node
 Composed of Data and Pointer. It connects with one another, and a set of them composes a list.

### Data
A component of a Node. Data content you want to separately store in a list structure.

### Pointer
Another component of a Node. With a pointer of a Node storing id info of one another, each of Nodes can connect in a sequential relationship.
