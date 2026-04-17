543. Diameter of the binary tree
<img width="1894" height="754" alt="image" src="https://github.com/user-attachments/assets/ba1bb6f4-b0f7-4e38-832c-2a698b58d212" />

In this problem, we have to find the diameter of binary tree i.e. length of longest path between any 2 nodes.

Approach: We operate under the logic that the diameter of any node is the max. height of left branch + max. height of right branch. We create a helper function height in which we perform dfs to find the diameter of each of the nodes and store the maximum diameter in global variable count. Then we call the height function in our original function for the root of the tree and return count.
