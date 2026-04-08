1047. Remove all adjacent duplicates in string

In this problem, we have to remove all adjacent duplicates from the string so that only the distinct elements remain and we have to return the updated string.

<img width="1904" height="808" alt="Screenshot 2026-04-08 144059" src="https://github.com/user-attachments/assets/ba3b2a39-b86c-470a-99e5-77a9fb203961" />

Approach: We take a stack rem. We push the characters of the string into the stack one by one. First, we check if the stack is empty or not. If it is, we push the character into the stack. If not, we check whether it matches the character at top then we pop() and push() according to that.

After we have deleted the duplicate characters, we put the remaining characters in a string and reverse it(to get the correct order). Then we return the final string.
