844. Backspace string compare
<img width="1899" height="810" alt="image" src="https://github.com/user-attachments/assets/3e80636b-d31d-40aa-96d3-9be4a96a5b90" />

In this problem, we have to check if two strings are equal when they are typed in text editors with backspaces as '#'.

Approach (Stack): We take 2 stacks stack1 (to store string s characters) and stack2 (to store string t characters). We loop through both strings, storing their characters in their respective stacks. If a '#' is encountered, the character at the top of stack is deleted (if stack is empty, nothing happens). Then we compare the 2 stacks to see if they are identical. If they are, we return true, else false.
