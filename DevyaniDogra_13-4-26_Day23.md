997. Find the town judge
<img width="1895" height="812" alt="image" src="https://github.com/user-attachments/assets/08a84909-8755-42fa-af7a-cada9213a3e3" />

In this problem, we have been given a matrix trust which has the relationships between the people of a town (who trusts who). We have to find the town judge (who everyone trusts but who trusts no one).

Approach: This situation can be represented as a directed graph where the incoming edges are the no. of people that trust that individual and outgoing edges are the no. of people the individual. We create 2 vectors in and out storing the no. of incoming and outgoing edges for the ith person of the town (looping through the vectors of trust). If there is an ith index with n-1 incoming edges and 0 outgoing edges, that is the town judge (return i). If not, there is no town judge (return -1)
