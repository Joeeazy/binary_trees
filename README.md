# General


What is a binary tree

A binary tree is a hierarchical data structure composed of nodes, where each node has at most two children, referred to as the left child and the right child. These children themselves are binary trees.




What is the difference between a binary tree and a Binary Search Tree

A Binary Search Tree (BST) is a specific type of binary tree where the value of each node in the left subtree is less than or equal to the node's value, and the value of each node in the right subtree is greater than the node's value. This property allows for efficient searching, insertion, and deletion operations.



What is the possible gain in terms of time complexity compared to linked lists

Compared to linked lists, binary trees can offer significant gains in terms of time complexity for certain operations. For example, in a binary search tree, the average-case time complexity for search, insertion, and deletion operations is O(log n), where n is the number of elements in the tree. This is significantly better than the O(n) time complexity of these operations in a linked list.



What are the depth, the height, the size of a binary tree

* Depth refers to the length of the path from the root to a particular node.

* Height refers to the length of the longest path from the root to a leaf node. Alternatively, the height of an empty tree is typically defined as -1.

* Size refers to the total number of nodes in the tree.



What are the different traversal methods to go through a binary tree

* Inorder traversal: Visit the left subtree, then the root, then the right subtree.

* Preorder traversal: Visit the root, then the left subtree, then the right subtree.

* Postorder traversal: Visit the left subtree, then the right subtree, then the root.

* Level order traversal: Visit nodes level by level, starting from the root.



What is a complete, a full, a perfect, a balanced binary tree

A complete binary tree is a binary tree in which every level, except possibly the last, is completely filled, and all nodes are as far left as possible. A full binary tree is a binary tree in which every node other than the leaves has two children. A perfect binary tree is both full and complete. A balanced binary tree is a binary tree in which the height of the two subtrees of any node never differs by more than one.
