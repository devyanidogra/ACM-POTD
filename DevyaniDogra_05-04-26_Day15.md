20. Valid Parentheses

<img width="1902" height="808" alt="image" src="https://github.com/user-attachments/assets/6b9f30f0-9843-4815-8732-858b4e1784c1" />

In this problem, we have to return true if the parentheses in the string are in valid order

Approach(Stack): We use a stack of characters called par. First, we put all the opening brackets into the stack. Then, we check whether the closing brackets match the opening brackets. If they do, we pop the opening bracket from the stack. At the end, if the stack is empty, that means all the brackets were valid so it returns true. Otherwise, it returns false.
