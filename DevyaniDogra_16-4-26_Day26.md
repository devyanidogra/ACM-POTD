226. Invert Binary Tree
<img width="1902" height="756" alt="image" src="https://github.com/user-attachments/assets/810ac344-c32e-4918-b158-c8d148ccd935" />

Approach: We swap the left children of the parent nodes with the right children (using temp node) by calling the function recursively for the left and right child of the root. The base case of the recursion is that if the root is null (leaf nodes have null children), it will return null. At the end, we return the root of the tree.
