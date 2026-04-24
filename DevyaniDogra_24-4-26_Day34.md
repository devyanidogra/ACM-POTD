198. House Robber
<img width="1900" height="803" alt="image" src="https://github.com/user-attachments/assets/86bba2a9-23f5-4c0d-930f-16b51f63892a" />

Approach: This uses a space-optimized dynamic programming approach to maximize the amount robbed without taking adjacent houses. It keeps track of two values: prev1 (max money up to the previous house) and prev2 (max up to the house before that). At each step, it decides whether to rob the current house (nums[i] + prev2) or skip it (prev1), choosing the max of the two, then updates the variables accordingly. In the end, prev1 holds the maximum money that can be robbed without triggering the alarm.
