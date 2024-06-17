# binary-expression-calc
# Binary-Tree-Expression-Calculator
It represents any polynomial equation in terms of BINARY TREE and solves all operations by evaluaying recursively the left and right sub-tree.

## TreeWalker.java

Treewalker file includes all operations on the binary tree-like rotation of tree, deleting or inserting a node into the tree, evaluating, differentiating, and simplifying.

Methods involve:

1Strategies include:


1. **open Position root(Position position):
**
Returns the root position(current) of a hub. In case it's not there, it'll make a hub.
2. **open Position parent(Position position:**

Returns the parent position of a hub at the current position. In case it's not there, it'll make a hub. It tosses an special case in the event that position id invalid.

3. **open Position leftChild(Position position):**
Returns the cleared out child of a hub at the current position. In the event that it's not there, it'll make a hub.

4. **open Position rightChild(Position position):**
Returns the cleared out child of a node at the current position. In the event that it's not there, it'll make a hub

5. **public Position rotateR(Position position):**
It turns a hub within the right heading raising its cleared out child to its position and bringing down itself to the proper.

6. **open Position rotateL(Position position):**
It turns a hub within the cleared out course raising its right child to its position and bringing down itself to the left.

7. **open Position first(Position position):**
It returns the primary position when the parallel tree is requested in Inorder traversal.

8. **public Position last(Position position):**
It returns the final position when the twofold tree is requested in Inorder traversal.

9. **open Position next(Position position):**
It returns the another position when the binary tree is requested in Inorder traversal. It makes a unused hub, if there's no another position i.e current position could be a leaf hub.

10. **open Position previous(Position position):**
It returns the past position when the twofold tree is requested in Inorder traversal. It makes a modern hub on the off chance that there's no past position i.e current position may be a root hub.

11. **open Position set(Position position):**
It sets the esteem of a position to be an integer inside its twofold look tree arrange and returns the same position with that esteem.

12. **open Position insert(Position position):**
It embeds a new node after the current hub concurring to the tree's Inorder Traversal arrange.

13. **open Position deleteNoRight(Position position):**
It erases the hub at the current position in the event that there's no right child of that hub.

14. **open Position deleteNoLeft(Position position):**
It erases the hub at the current position on the off chance that there's no left child of that hub.

15. **open Position delete(Position position):**
It deletes the hub at the current position when the hub has no children. On the off chance that the node has an as it were cleared out child, at that point inquired deleteNoRight() to do it, and on the off chance that it as it were has a right child, at that point it'll ask strategy deleteNoLeft() to do it.
 
16. **open int evaluate(int x, int y, int z):**
It performs the operation given as the esteem the hub at the current position on its children recursively, at the conclusion fathoming the entire condition communicated as a parallel tree and returns the resultant numbers esteem. For case, in case the current hub has esteem '+', at that point it'll perform expansion on its left and right child. And if the current node's esteem isn't an numbers esteem rather than that operation image, at that point it returns that numbers value as yield. It may be a recursive strategy. It takes the position of the hub we ought to assess, and the three numbers values included the calculation as a Parameter. It too takes the assistance of a aide strategy "open int eval(Position f, int x, int y, int z)".

17. **open void separate():**
Utilizing the aide strategy "open BTNode differentiatehide(BTNode f)" which takes the position of the hub as a parameter and separates the total condition assist from the given hub taking after diverse rules for separation and returns the resultant expression in terms of the twofold tree. It may be a recursive strategy. Rules of separation:

Whole Run the show:
(f+g)' = f' + g'

Contrast Run the show:
(fg)' = f g' + f' g

Remainder Run the show:
(f/g)' = (f' g − g' f )/g^2

"open BTNode copy(BTNode f)" is a aide strategy that makes a difference to make a deep copy of the hubs.

18. **open void rearrange():**
It simplifies the polynomial condition given and yields the resultant condition in the form of a binary tree utilizing the partner strategy "open BTNode simplifyhide(BTNode f)". It could be a recursive strategy.
 
