189. Rotate Array
<img width="1897" height="809" alt="image" src="https://github.com/user-attachments/assets/26f8ea0e-b8f8-4ac7-80ca-ca6cbdb4a0a2" />

In this problem, we have to rotate array by k steps to the right so that all the elements move by k spaces.

Approach: We use a temporary array temp with size k, where we store the last k values of nums (using for loop). then we copy the remaining n-k elements k steps to the right (using for loop). Then we copy the values from temp onto the original array.
