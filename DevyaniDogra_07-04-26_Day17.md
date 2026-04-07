225. Implement stack using queue
<img width="1903" height="808" alt="image" src="https://github.com/user-attachments/assets/0b9d8d07-0266-49c5-b3ef-0ad665851eb1" />

In this problem, we have to implement the behavior of a stack (LIFO) using only 2 queues.

Approach: We take 2 queues q1 and q2. q1 is used to push the elements in and q2 is used to bring the top value forward for pop() and top() functions.
1. when push() is called, element is pushed to q1
2. when top() is called, all the elements of q1 are pushed into q2 except the last element(the top of stack) which is saved in a variable a, then pushed to q2. Then, the elements are pushed from q2 back to q1.
3. when pop() is called, the process is the same as top but the top element saved in variable a is popped.

