1021. Remove outermost parentheses
<img width="1899" height="804" alt="image" src="https://github.com/user-attachments/assets/ea5040db-9c6c-4873-ae2f-125ccbf45fe4" />

In this problem, we are given strings of brackets which are made up of valid parentheses strings. We need to remove the outermost parentheses of each of the valid parentheses string concatenated in the string.

Approach(Stack): We take a stack rem. We loop through the string. if the character is '(' and the stack isnt empty, we add it to the final string (inner bracket). Then we push it into the stack. If the character is ')', we pop the character at top. If the stack is not empty, we add it to final string.
