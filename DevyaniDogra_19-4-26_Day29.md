509. Fibonacci Number
<img width="1902" height="752" alt="Screenshot 2026-04-19 183454" src="https://github.com/user-attachments/assets/1a77010c-0f91-45b1-a8a0-1a5c1018fbc5" />

In this problem, we have to find the nth fibonacci number (sum of the previous 2 no.s in the sequence)

Approach (Iterative): We take 3 variables f1(initialised as 0), f2(initialised as 1) and f. We calculate f as the sum of f1 and f2 in a loop running n-1 times. Then we assign f1 the value of f2 and f2 the value of f. At the end, we return f.
