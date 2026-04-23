746. Min cost climbing stairs
<img width="1904" height="809" alt="image" src="https://github.com/user-attachments/assets/878670e3-0eee-4a2c-b6ff-f12fa948c62f" />

Approach: This uses a space-optimized dynamic programming approach where instead of storing the minimum cost for every step, it only keeps track of the last two costs. At each step, it calculates the current minimum cost as cost[i] + min(a, b), since you can reach the step either from one step before or two steps before, and then updates the variables by shifting them forward. In the end, since you can reach the top from either of the last two steps, it returns min(a, b) as the final answer.
