1346. Check if n and its double exists
<img width="1892" height="758" alt="image" src="https://github.com/user-attachments/assets/165ed174-beda-4dc7-a4cd-0e493931f485" />

In this problem, we have to search if the array has two indices where a value n and its double 2n is stored.

Approach (HashSet): We define an unordered set x. Using a for loop, we check if the set either has the double of a number in array or the half(for even no.s only). If found, we return true. If not, we add the number to x.
If, at the end of the loop, their are no such no.s, function returns false.
