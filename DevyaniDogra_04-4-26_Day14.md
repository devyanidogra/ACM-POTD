234. Palindrome linked list
<img width="1898" height="815" alt="image" src="https://github.com/user-attachments/assets/5d5c2676-8229-441f-b1ab-676732e819f5" />

In this problem, we have to check if the list is a palindrome or not (same in reverse order)

Approach: We first find the middle of the linked list (by slow and fast method or by count method) so that we can reverse the second half of the linked list. Then we compare the second half of the linked list with the first half. If they are equal, then the list is a palindrome (return true), else return false.

This approach takes O(N) time and O(1) space complexity
