# JavaScript-Palindrome-Checker
This a freecodecamp JavaScript Project
A Palindrome is a word spelled the same way both forward and backwards, ignoring case,punctuation and spacing
1. We use a regex expression to polish the string. For example we use (W) letter in the regex to remove whitespaces in words.








![JavaScript-Algorithms-and-Data-Structures-Projects-Palindrome-Checker-freeCodeCamp-org](https://user-images.githubusercontent.com/73931581/229345534-c3f13d8d-6c15-4bb9-97e5-816ee31ef02c.png)

2. We use (+) sign in the regex so as to capture multiple whitespaces in words.
3. We use (| _ ) operator to take care of words with underscores.
4. We then use the (g) sign to make it global.
5. We then use (.toUpperCase) to convert the words to uppercase.
6. The (.split("")) method splits the words into single letter strings.
7.The (.reverse()) method starts the words from backwards to forwards instead of vice-versa.
8. The (.join("")) method joins the multiple words together.
