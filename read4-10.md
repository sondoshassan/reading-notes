# summary class 09

## Stack
is a data structure. has a node each node refrence to the next node just. 
the main terminologies of stack are  push (to add node on stack), pop (to delete nose from stack), peek (view top node) and peek (to view top node in the stack) and isEmpty return true when the stack is empty.
#### FILO 
that means first one added, last one popped.
#### LIFO
the opposite of FILO. that means last one added will be first one popped out.
#### push
is always O(1). when using push will add node at the top of stack and the next will be the original node.
#### pop 
before using pop you should check if the stack empty by using `isEmpty`. the step to do that create refrence named `temp` points on the top node. then re-assigned the next node to be top node.
#### peek 
also u need to check if the stack is empty by using `isEmpty`.

## Queue
the main terminologies of queue are *Enqueue* (add), *Dequeue* (delete), *Front* (first node), *Rear* (last node), Peek (view the value of front node) and *IsEmpty* to check if the queue is empty.
#### FIFO 
first item in the queue will be the first item out of the queue.
#### LILO
last item in the queue will be the last item out of the queue.
#### Enqueue
O(1). first change the next to point we are adding by using `rear.next`. the new node will be has a value and next null.
#### Dequeue
O(1). Before any thing u need to check if is empty `isEmpty`. create refrence name `temp` and point on front node. then assigned front to *front.next*  and *temp.next* to null. then return the value of the temp Node that was just removed.
#### peek
O(1). check if the queue is empty by using `isEmpty`. do not re-assign the next property when we peek because we want to keep the reference to the next Node in the queue.


