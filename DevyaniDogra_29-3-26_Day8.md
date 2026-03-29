206. Reverse a linked list
<img width="1902" height="814" alt="image" src="https://github.com/user-attachments/assets/3b1c3e42-aa3d-4b53-a8c6-15931fbf8636" />

In this problem, we have to reverse the given linked list and return the head of the reversed linked list

Approach: We initialise 3 pointers prev (= NULL), curr (= head) and next (= NULL). Running a while loop while curr is not null, we 
1. Save the next node first
2. Point the current node towards the previous node
3. Reinitialise prev and curr by moving them one step forward

Then we return prev because in the reversed list, prev will point towards the head of the list.
