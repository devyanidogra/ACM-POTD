1544. Make the string great
<img width="1896" height="809" alt="image" src="https://github.com/user-attachments/assets/6426df62-7729-402d-8da8-ff811ed32e70" />

In this problem, we have to make the string "good" by removing the characters which are upper and lower case of the same letter and adjacent to each other.

Approach: We take an empty string final into which we will pu the characters of the good string. We run a loop through the characters of the original string s and compare the current character to the last character pushed into final (using ASCII codes). If they are upper and lower case versions of the same letter, the last character of final is deleted. If not, the character from string s is pushed into final. Then, the final string is returned.
