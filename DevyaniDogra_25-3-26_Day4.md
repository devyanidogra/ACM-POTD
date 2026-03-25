268. Missing number
<img width="1889" height="805" alt="image" src="https://github.com/user-attachments/assets/543186db-4a81-4a4f-9a18-70c3c721c0ec" />

In this problem, we are given an array with n distinct numbers ranging from 0 to n. As there are only n-1 slots in the array, there will be a missing number which we have to find.

Using sorting: We first sort the array using the sort() function. then we take a variable value in order to check which value within the range of numbers is missing. We do this using a for loop. If all the values from 0 to n-1 are present, then n itself will be missing, and is then returned. this has O(nlogn) time complexity
