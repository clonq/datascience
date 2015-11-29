Binary Trees
===

A `binary tree` is a tree data structure in which each node has at most two children, which are referred to as the left child and the right child.

A `full binary tree` or `proper` or `plane binary` tree is a tree in which every node in the tree has either 0 or 2 children.

A `perfect binary tree` is a binary tree in which all interior nodes have two children and all leaves have the same depth or same level.

In a `complete binary tree` every level, except possibly the last, is completely filled, and all nodes in the last level are as far left as possible. It can have between 1 and 2h nodes at the last level h. An alternative definition is a perfect tree whose rightmost leaves (perhaps all) have been removed.

A binary tree is called an `almost complete binary tree` or `nearly complete binary tree` if the last level is not completely filled.

In the `infinite complete binary tree`, every node has two children.

A `balanced binary tree` has the minimum possible maximum height (a.k.a. depth) for the leaf nodes, because for any given number of leaf nodes the leaf nodes are placed at the greatest height possible.

A `degenerate` or `pathological` tree is where each parent node has only one associated child node.

A tree consisting of only a root node has a height of 0.

The number of nodes n in a full binary tree, is at least n = 2h+1 and at most n = 2^(h+1) - 1, where h is the height of the tree.

The number of leaf nodes l in a perfect binary tree, is l = (n + 1) / 2.

In a language with records and references, binary trees are typically constructed by having a tree node structure which contains some data and references to its left child and its right child. Sometimes it also contains a reference to its unique parent.

A `threaded binary tree` is a binary tree variant that allows fast traversal: given a pointer to a node in a threaded tree, it is possible to cheaply find its in-order successor (and/or predecessor).

Binary trees can also be stored in breadth-first order as an implicit data structure in arrays, and if the tree is a complete binary tree, this method wastes no space. In this compact arrangement, if a node has an index i, its children are found at indices 2i + 1 (for the left child) and 2i + 2 (for the right).

