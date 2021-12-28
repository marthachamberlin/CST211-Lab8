# CST211-Lab8
Lab 8
AVL Tree
Description
Create an AVL Tree ADT as discussed in class. This data structure should have all of the functionality of the Binary Search Tree.
Stipulations
You must include the following functions.
* Insert
* Delete
* Purge
* Height
* InOrder Traversal
* PreOrder Traversal
* PostOrder Traversal
* BreadthFirst Traversal
* Appropriate Manager Functions

Do not use a threaded tree.

All traversal functions must accept a function pointer to the visit function to be called. See the example below.
* //BSTree method 
* void BSTree::InOrder(BSNode* root, void (*visit)(T data))
* {
* }
* //Consumer function
* void Display(int data)
* {
* 	cout << data << endl;
* }

* //Consumer call to the InOrder traversal
* bst.InOrder(Display);

Deliverables
One file including:
* Your code
* Your test(s) similar to Lab1_test.cpp & Lab2_test.cpp and their results

Extra Credit
* 5 pts. Write an iterative height function as well as a recursive height function.
* 25 pts. Write the insert in the “efficient” method (without using a height function).

Similar Deliverables
