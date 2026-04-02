82. Remove duplicates from sorted list 2
<img width="1905" height="811" alt="image" src="https://github.com/user-attachments/assets/a548b442-ce0d-4e27-b0d5-e06cf0a3d20e" />

In the problem, we need to remove all instances of any node that is duplicated.

Approach: we take a dummy node before head to handle the edge case of deleting at the front of the list. We take 2 pointers x(dummy) and curr(head). we compare values of curr and the node next to it:
1. If they arent equal, move x and curr up a step
2. If they are equal, we move the curr pointer until the duplicates end, after which x will be connected to the distinct node

We take another if statement to handle the case of deleting at ends.

This approach takes O(N) time
