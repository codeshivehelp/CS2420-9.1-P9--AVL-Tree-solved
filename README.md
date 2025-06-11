# CS2420-9.1-P9--AVL-Tree-solved

Download Here: [CS2420 9.1 P9 -AVL Tree solved](https://jarviscodinghub.com/assignment/9-1-p9-avl-tree-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Project 9 Balanced Binary Tree
AVL Trees
The standard template library is not to be used in this assignment or any other assignment unless expressly stated
AVL Trees
Implement an AVLTree class that stares an integer as a data type. Including the fallowing functions:
Constructor
• Destructor
• Insert
• Print (indented print function like the one we did in class, but with each node’s height)
• PreOrderTraversal
• Node* GetRootO { return root, // needed for unit Testing
plus all other functions needed to properly implement an AVL balanced BSI
Also implement a Node class appropriate with this assignment. The supplied Template far Node_h *includes “Observer h’ and defines a
member variable of type Observer Your Node h MUST do the same This is needed far unit Testing of your AVL Tree. In addition to
whatever you feel needed, you MUST have the following three public data members name EXACTLY as follows:
• int value;
• Node* left.
• Node* right;
These are needed to be named this way so that the Llnit Testing will nork.
Testing
The supplied Main_cpp should properly compile and pun when added to pur files You must not modify Main cgg to get it to compile
and run. When mainO runs it will create several AVLTrees and add data to eactl After adding data, the tree will be traversed (with
PreOrderTraversal()). When the final tree is traversed, it will also print that tree.
The output should look like this:
32
25,
2e
2e,
25,
14,
14
17,
15,
15,
15,
15,
4,
(3)
89,
le,
le,
15,
2e,
25,
3e,
22,
3e,
30,
22,
25,
25,
7,
35,
3e,
35,
35,
4e, 35, 45,
le, 21, 15, 18,
28,
26,
[leaf]
[Empty]
7 (B) [leaf]
1B (e) [leaf]
21 (2)
15 (1)
[ Empty ]
18 (e) [leaf]
28 (1)
26 (e) [leaf]
