876. Middle of the linked list
<img width="1896" height="760" alt="image" src="https://github.com/user-attachments/assets/36ffcd9b-2739-4fe9-8746-017cc0fe4945" />


In this problem, we have to return the middle node of the linked list (2nd middle in case of even no. of nodes)

Approach: We take two pointers x and y and a variable count. x will be used to figure out the length of the linked list, which will be stored in count. The count will then be halved to find the halfway point. Then y will be used to find the middle (in a while loop) and then be returned. This takes O(N) time.
