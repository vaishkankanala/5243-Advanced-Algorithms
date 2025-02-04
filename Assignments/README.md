## Node Deletion in a Binary Search Tree (BST)

### 1. Base Case: Empty Tree
##### If the tree is empty (root is nullptr), the function returns, as there's nothing to delete.

### 2. Searching for the Node
###### The _delete function recursively traverses the tree:
       ->If the target value is less than the current node's value, the search continues in the left subtree.
       ->If the target value is greater than the current node's value, the search continues in the right subtree.
   
### 3. Node Found: Handling Different Cases
##### When the node to be deleted is found, the function handles three cases:
      ->No Left Child: If the node has no left child, its right child (or nullptr if it has no children) takes its place. The node is deleted, and the parent's pointer is updated.
      ->No Right Child: If the node has no right child, its left child takes its place. The node is deleted, and the parent's pointer is updated.
      ->Two Children (Both Left and Right Exist):
        This is the most complex case:
          Finding Inorder Successor: The inorder successor (the smallest node in the right subtree) is located using the minvalue function.
          Replacing Node Value: The value of the node to be deleted is replaced with the value of the inorder successor.
          Deleting Inorder Successor: The original inorder successor node is then deleted from the right subtree using a recursive call to _delete. This ensures that the successor's original position is cleaned up.
   
### 4. Maintaining BST Property
##### The choice of the inorder successor ensures that the BST property (left subtree < node < right subtree) is preserved after deletion.


## Challenges
#### I found it hard to understand the recursive call for inorder transversal.
#### other than that deletion was easy for all cases.


### Written by: Vaishnavi Kankanala
