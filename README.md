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

Sample Input 0

F:6,D:4,C:3,B:2,A:1,E:5,I:9,G:7,H:8,J:10
G
Z
-
-
-
-
-
-
Sample Output 0

Enter a list of key:value pairs separated by commas:
Input key for get() method:
The value of G is 7
Input key for get() method:
The value of Z is None
Input key for size() method:
Input key for depth() method:
Input key for height() method:

The preOrder traversal is ['F:6', 'D:4', 'C:3', 'B:2', 'A:1', 'E:5', 'I:9', 'G:7', 'H:8', 'J:10']
The inOrder traversal is ['A:1', 'B:2', 'C:3', 'D:4', 'E:5', 'F:6', 'G:7', 'H:8', 'I:9', 'J:10']
The postOrder traversal is ['A:1', 'B:2', 'C:3', 'E:5', 'D:4', 'H:8', 'G:7', 'J:10', 'I:9', 'F:6']

Input key for delete() method:
Input key for delete() method:
Test balanced Tree?
Sample Input 1

F:6,D:4,C:3,B:2,A:1,E:5,I:9,G:7,H:8,J:10
-
-
I
H
F
-
-
-
Sample Output 1

Enter a list of key:value pairs separated by commas:
Input key for get() method:
Input key for get() method:
Input key for size() method:
The size of I is 4
Input key for depth() method:
The depth of H is 3
Input key for height() method:
The height of F is 4

The preOrder traversal is ['F:6', 'D:4', 'C:3', 'B:2', 'A:1', 'E:5', 'I:9', 'G:7', 'H:8', 'J:10']
The inOrder traversal is ['A:1', 'B:2', 'C:3', 'D:4', 'E:5', 'F:6', 'G:7', 'H:8', 'I:9', 'J:10']
The postOrder traversal is ['A:1', 'B:2', 'C:3', 'E:5', 'D:4', 'H:8', 'G:7', 'J:10', 'I:9', 'F:6']

Input key for delete() method:
Input key for delete() method:
Test balanced Tree? 
Sample Input 2

F:6,D:4,C:3,B:2,A:1,E:5,I:9,G:7,H:8,J:10
-
-
-
-
-
-
-
-
Sample Output 2

Enter a list of key:value pairs separated by commas:
Input key for get() method:
Input key for get() method:
Input key for size() method:
Input key for depth() method:
Input key for height() method:

The preOrder traversal is ['F:6', 'D:4', 'C:3', 'B:2', 'A:1', 'E:5', 'I:9', 'G:7', 'H:8', 'J:10']
The inOrder traversal is ['A:1', 'B:2', 'C:3', 'D:4', 'E:5', 'F:6', 'G:7', 'H:8', 'I:9', 'J:10']
The postOrder traversal is ['A:1', 'B:2', 'C:3', 'E:5', 'D:4', 'H:8', 'G:7', 'J:10', 'I:9', 'F:6']

Input key for delete() method:
Input key for delete() method:
Test balanced Tree? 
Sample Input 3

F:6,D:4,C:3,B:2,A:1,E:5,I:9,G:7,H:8,J:10
-
-
-
-
-
G
D
-
Sample Output 3

Enter a list of key:value pairs separated by commas:
Input key for get() method:
Input key for get() method:
Input key for size() method:
Input key for depth() method:
Input key for height() method:

The preOrder traversal is ['F:6', 'D:4', 'C:3', 'B:2', 'A:1', 'E:5', 'I:9', 'G:7', 'H:8', 'J:10']
The inOrder traversal is ['A:1', 'B:2', 'C:3', 'D:4', 'E:5', 'F:6', 'G:7', 'H:8', 'I:9', 'J:10']
The postOrder traversal is ['A:1', 'B:2', 'C:3', 'E:5', 'D:4', 'H:8', 'G:7', 'J:10', 'I:9', 'F:6']

Input key for delete() method:
Deleting G is True
The preOrder traversal is ['F:6', 'D:4', 'C:3', 'B:2', 'A:1', 'E:5', 'I:9', 'H:8', 'J:10']
The inOrder traversal is ['A:1', 'B:2', 'C:3', 'D:4', 'E:5', 'F:6', 'H:8', 'I:9', 'J:10']
The postOrder traversal is ['A:1', 'B:2', 'C:3', 'E:5', 'D:4', 'H:8', 'J:10', 'I:9', 'F:6']
Input key for delete() method:
Deleting D is True
The preOrder traversal is ['F:6', 'E:5', 'C:3', 'B:2', 'A:1', 'I:9', 'H:8', 'J:10']
The inOrder traversal is ['A:1', 'B:2', 'C:3', 'E:5', 'F:6', 'H:8', 'I:9', 'J:10']
The postOrder traversal is ['A:1', 'B:2', 'C:3', 'E:5', 'H:8', 'J:10', 'I:9', 'F:6']
Test balanced Tree? 
Sample Input 4

F:6,D:4,C:3,B:2,A:1,E:5,I:9,G:7,H:8,J:10
-
-
-
-
-
-
-
Y
Sample Output 4

Enter a list of key:value pairs separated by commas:
Input key for get() method:
Input key for get() method:
Input key for size() method:
Input key for depth() method:
Input key for height() method:

The preOrder traversal is ['F:6', 'D:4', 'C:3', 'B:2', 'A:1', 'E:5', 'I:9', 'G:7', 'H:8', 'J:10']
The inOrder traversal is ['A:1', 'B:2', 'C:3', 'D:4', 'E:5', 'F:6', 'G:7', 'H:8', 'I:9', 'J:10']
The postOrder traversal is ['A:1', 'B:2', 'C:3', 'E:5', 'D:4', 'H:8', 'G:7', 'J:10', 'I:9', 'F:6']

Input key for delete() method:
Input key for delete() method:
Test balanced Tree? 
The preOrder traversal is ['D:4', 'B:2', 'A:1', 'C:3', 'H:8', 'F:6', 'E:5', 'G:7', 'I:9', 'J:10']
The inOrder traversal is ['A:1', 'B:2', 'C:3', 'D:4', 'E:5', 'F:6', 'G:7', 'H:8', 'I:9', 'J:10']
The postOrder traversal is ['A:1', 'C:3', 'B:2', 'E:5', 'G:7', 'F:6', 'J:10', 'I:9', 'H:8', 'D:4']
