141. Linked list cycle

In this problem, we have to find out if the linked list has a cycle or not (if you can reach an already visited node again as tail of a node points to it).

Approach 1 (Hash Table): In this, we use a hash table to store all the pointers of the nodes already visited and compare them against the current node in a loop. This approach takes O(N) time but also takes O(N) space.

<img width="1897" height="811" alt="Screenshot 2026-03-30 200532" src="https://github.com/user-attachments/assets/709dcba7-9010-4b10-87a3-e02530d2631e" />


Approach 2 (Floyd's cycle detection algorithm): In this, we use two pointers slow (moving 1 step) and fast (moving 2 steps). This uses the idea that if there is a cycle present, the slow and fast pointers will eventually meet. We will check if slow == fast, if true, return true. If fast reaches NULL, return false. This approach also takes O(N) time but takes O(1) space.

<img width="1890" height="754" alt="Screenshot 2026-03-30 204955" src="https://github.com/user-attachments/assets/2923168c-1624-4156-a978-9c6689a5c619" />

