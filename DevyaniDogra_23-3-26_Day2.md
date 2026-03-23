<img width="1677" height="775" alt="image" src="https://github.com/user-attachments/assets/3a09d5fa-c439-492c-9cf1-067cfd6ab327" />

in the given problem, we have a sorted array from which we have to remove duplicates and return number of unique elements. we use a two pointer approach in this. we use variable temp, initialised at 0 which is compared in a loop with i. if value at temp index is not equal to value at ith index, the temp variable is incremented and the value of nums[i] is assigned to nums[temp] .
