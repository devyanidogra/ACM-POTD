83. Remove duplicates from sorted list
<img width="1887" height="756" alt="image" src="https://github.com/user-attachments/assets/5e781dfe-1733-42a4-8c3e-fd9e66ae7cb6" />

In this problem, we have to remove all the duplicate nodes from the sorted list so that all the nodes are unique and in sorted order as well.

Approach: We take two pointers x and curr where values of x and curr are compared while curr is not not null. If the values are equal, the curr node is deleted by:
1. Defining a node to be deleted later nodeDel and storing curr in it
2. updating x->next to the node after curr
3. moving current forward
4. deleting nodeDel

If values are not equal, values are moved forward. The time complexity is O(N).

