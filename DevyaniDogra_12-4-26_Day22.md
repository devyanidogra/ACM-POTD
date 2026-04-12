733. Flood fill

![Screenshot_20260412_223426_Samsung Internet](https://github.com/user-attachments/assets/af5bf034-bc04-49bf-863b-6c4af8bf3c37)


In the problem, we are given an image matrix, a color and the indexes for the source element. We have to turn the adjacent elements to the source element with the same number into the color as well as their adjacent with the same original no. (performing a flood fill)

Approach: We conduct a depth first search by creating a function dfs in which we turn the elements into the color that fulfill the flood fill requirement. Then we recursively call the function for its adjacent elements until it goes out of bounds or doesn't fulfill the flood requirement.
