121. Best time to buy and sell stock
In this problem , we are given an array which represent price of a stock at a particular day. we have to find the best day to buy and sell that stock to earn maximum profit.

Brute force approach: In this, we do a nested for loop to compare all possible combinations of buy and sell days. This takes n^2 time and exceeds the time limit.

Optimal approach(Dynamic programming): we can use dp to solve this problem by initialising a variable buy which represents the buying price as we go through the array. buy is updated if we encounter a smaller value along the array using a for loop. the current profit and the profit are compared in every iteration to save the max profit, which is then returned.

<img width="1897" height="821" alt="image" src="https://github.com/user-attachments/assets/ced68b23-4647-406d-9e03-2468b763c1ce" />

