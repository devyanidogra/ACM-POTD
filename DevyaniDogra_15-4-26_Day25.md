104. Maximum depth of binary tree
<img width="1903" height="758" alt="image" src="https://github.com/user-attachments/assets/033a61b0-847a-491b-aa09-d39d9bddb31c" />

In this problem, we have to find the no. of nodes present in the longest path from root to the farthest leaf node.

Approach: We use recursive dfs to solve this problem. We call the maxDepth recursively for the left child and right child to find the maximum childrens height. Then we return max(childrens height) + 1 for the root. The base case is if the node is null(leaf nodes have null children), then return 0.
