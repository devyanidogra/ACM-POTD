283. Move zeroes
<img width="1896" height="816" alt="image" src="https://github.com/user-attachments/assets/d9a66167-c638-451f-ae34-eb7641d07ce6" />
In this problem, we have to move all the zeroes of the array to the end while also maintaining the relative order of the other elements.
Approach: To solve this, we take a counter count which keeps track of the number of 0s in the array, and a variable st which keeps track of location of the non zero elements. We run 2 for loops, one to move the non zero elements to their position and the other to put the 0 elements at the end based on count.

