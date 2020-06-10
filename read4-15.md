# summary class 15

## Trees
### Common Terminology
- Node (indevisual item make data structure).
- Root (first node in tree).
- Left Child (left node).
- Right Child (right node).
- edge (link between child and parent).
- Leaf (node dosen't cotain any child).
- Height (number of edges).

### Traversals
#### Depth First
use call stack
we have three method of depth first:
- Pre-order: root >> left >> right
- In-order: left >> root >> right
- Post-order: left >> right >> root

##### pre-order
first in the call stack will contain the root. then check if our root has a left then make it as a root, then start with leaves at first take the left then right, now go to the right node and make it as root.

#### Breadth First
use queue.
first dequeue the first node (root) and enqueue the left then right and reapet the enqueue and dequeue for the children and reset the front of stack.

#### Binary Trees
Trees can have any number of children per node, but Binary Trees restrict the number of children to two.
**thats no matter where u can but the new node just fill the cheldren**
the BigO for adding node is O(n) because we search where we can put the node.

#### Binary Search Trees
nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.
BigO time O(log n), space O(1)


