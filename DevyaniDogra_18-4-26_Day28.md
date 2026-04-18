572. Subtree of another tree
<img width="1903" height="756" alt="image" src="https://github.com/user-attachments/assets/ab9b592a-2cc7-43ab-af53-8b9391106335" />

Approach: We define a helper function isIdentical which checks if two trees are identical or not by comparing the root nodes as well as the left and right subtree through recursion. The base case is that if both the nodes are null, it is identical but if only one of the nodes is null, they are not identical.

In the isSubtree function, we recursively call the function for all nodes.
