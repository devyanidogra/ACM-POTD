1791. Find center of star graph
<img width="1895" height="804" alt="image" src="https://github.com/user-attachments/assets/57512861-1a41-4314-81f7-5d3eb789876b" />

In this problem, we are given an undirected star graph and we have to figure out the number (from 1 to n) at the center of star graph (center is connected to n-1 nodes).

Approach: To find the center of the graph, we need to find the node that appears in every single one of the edges in the 2d array edges. We take integer a and b as the first and second nodes of the first edge. Then, we compare it with the nodes of the 2nd edge. If one of them is repeated in the next edge, they are the centre (only center has more than one edge)
