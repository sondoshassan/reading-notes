## Linked List

it is linked each nodes with the next. we have two types of Linked, which is *singly* and *doubly*. the singly mean it has one refrence which refer to the next node but the doubly has two refrence refer to previous and next.

### Traversal
you not able to use for or forEach you will use the next node. so will use `while()`.
if we need to add new node at the begining we need to change the refrence of this node and make it header. we used add() methtod for this.
to add node at the midle we can use AddBefore or AddAfter.
to print all the node we use Find() method.

## more about linked list
the types of data structur are array, object, hashes and variables. when the data arrange non linear it calld non-sequentially. hashes, graph and tree is a non-linear data. linked list use less of memory data. linked list is a dynamic data structure this mean it can shrink or grow. we have circular linked list which is didn't end with last node(nall).

Big O is the method to describe the efficient of time in the memory. for Big O we have O(n) function. n it maybe be 1, n^2, n. the worst case when the n ==> n^2 > n > 1.

the procedure when you work whith singly linked and you want to add node at the start it is first find head note, then make new node, and set its pointer to the current first node of the list finally rearrange our head node’s pointer to point at our new node. add element at the begining is more efficient.

the procedure when you work whith singly linked and you want to add node at the end it is find the node we want to change the pointer of (in this case, the last node), then create the new node we want to insert and set its pointer to null finally direct the preceding node’s pointer to our new node.

