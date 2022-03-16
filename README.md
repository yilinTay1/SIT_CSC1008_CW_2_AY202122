# AY202122_CSC1008_Coursework_2
Binary Search Tree 
An example of Binary Search Tree (BST) is shown as follows, where A,B,F,E,K are keys, while 3,4,5,6,9 are their corresponding values.

      B:4
     /   \
   A:3   F:5
        /   \
       E:6  K:9
A default createTree() method has been implemented, you are required to implement the following functions of a Binary Search Tree (BST):

1.Search for a key - implement get() method to search for the value of a given key in the BST. For example, get("B") for the tree will return 4. For key not in the BST, get() method should return None. [10 marks]

2.Finding the size of a subtree in BST - implement a recursive size() method to determine the number of nodes in a subtree. For example, size("B") for the tree will return 5. [5 marks]

3.Finding the depth of a node in BST - implement a recursive depth() method to calculate the depth of a given key in the BST. For example, depth("A") for the tree will return 1. For item not in the BST, the depth() method should return None. [5 marks]

4.Finding the height of a Node in BST - implement a recursive height() method to calculate the height of a given key in the BST. For example, height("B") for the tree will return 2, while height("A") will return 0. For item not in BST, the height() method should return None. [5 marks]

5.PreOrder, InOrder and PostOrder Traversal of Tree - implement the recursive preOrder(), inOrder() and postOrder() methods. [20 marks]

6.Deleting an item in BST - implement the delete() method to delete a key from the BST. The delete() method should return True if the key has been deleted from the BST or False if the key does not exist in the BST. [25 marks]

7.Create a balanced Search Tree (AVL Tree) - this method ensures that the BST generated is always balanced. You should implement rotateLeft(), rotateRight(), etc to ensure that when inserting a node into the tree, it results in a balanced tree. Note that in a balanced BST, the depth of any two leaf nodes differs by at most 1. (please refer to the visualisation of AVL here - https://www.cs.usfca.edu/~galles/visualization/AVLtree.html) [30 marks]

Input Format

1: list of key-value pairs separated by comma
2: get() - input key or '-'
3: get() - input key or '-'
4: size() - input key or '-'
5: depth() - input key or '-'
6: height() - input key or '-'
7: delele() - input key or '-'
8: delete() - input key or '-'
9: createBalancedTree() - 'Y' or '-'

Constraints

nil

Output Format

nil
