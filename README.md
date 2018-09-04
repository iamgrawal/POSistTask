# POSistTask

## Task

A new node, D with its parent as A, cannot have a value greater than 30 (17 + 10) = 3. This is true for all new child nodes that will be created. Sum of a set of value of siblings should never be greater than the value of the root node.
At any point of time, the sum of all values of nodes should never be larger than the value of the genesis node.
Using data structure and programming language of your choice, design an efficient application that realises the following tasks:
  1. Create the Genesis Node. Genesis Node has parent node as null.
  2. Create set of child nodes of a particular node.
  3. Create a child node that originates from a particular node.
  4. Encrypt and decrypt the data inside the node.
  5. Verify the owner of the node, with the encryption key. Symmetric encryption shows the data. The integrity of the data is checked by computing the hash value of the data and checking with the already computed hash.
  6. Edit value of a node. Editing can have many forms, edit value of a subtree root, trickle down the subtree node value to a set of children, or one child or edit value of a leaf node.
  7. Transfer ownership of a particular node value. The previous owner validates his/her ownership by decrypting the data, and comparing the hash values. The new owner then encrypts the data with his key.
  8. Find the longest chain of the genesis node.
  9. Find the longest chain of any node.
  10. Merge 2 nodes: data is added of the 2 nodes, ownership of the longer chain node are retained after a merge operation.