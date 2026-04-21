70. Climbing stairs
<img width="1906" height="810" alt="image" src="https://github.com/user-attachments/assets/8f95cb2a-c74b-4c24-aa1f-58354a6ca593" />

In this problem, we are given the number of stairs and we have to figure out how many ways there are to climb to the top if you can take either 1 or 2 steps.

Approach: The number of ways to climb n stairs can be written as ways(n) = ways(n-1) + ways(n-2) which is the equation for fibonacci sequence. So ways(n) = fib(n+1). 
