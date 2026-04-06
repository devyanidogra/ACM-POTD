232. Implement queue using stacks
<img width="1902" height="804" alt="Screenshot 2026-04-06 023311" src="https://github.com/user-attachments/assets/f5c45d89-fc44-4fb3-a855-b5761cd42e13" />

In this problem, we have to implement the behavior of queue (FIFO) using only 2 stacks. It should support all the functions of a normal queue.

Approach: We create 2 stacks s1 and s2. s1 will be used for pushing elements onto the queue and s2 will be used for pop and peek functions. 
1. When push() is called, the element will be pushed to s1 stack.
2. when pop() and peek() is called, if s2 is empty, all values from s1 will be popped from s1 and pushed to s2 (to reverse their order). If s2 is not empty, the value at top will directly be taken and returned (or popped, in case of pop()).
3. when empty() is called, if both the stacks are empty, then the queue is empty (there are no duplicates of an element. if an element is moved to a different stack, its appearance in the original is deleted.
