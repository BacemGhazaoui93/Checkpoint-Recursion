1.	This algorithm takes a string word as input and returns a boolean value true if the word is a palindrome and false otherwise.
2.	It first checks if the length of the word is less than or equal to 1, in which case it always returns  as the word is a palindrome by definition in this case
3.	Otherwise, it initializes two variables start and end to the start and end positions of the word
4.	It then enters a loop, which continues until the start position is greater than the end position. 
5.	Within the loop, it checks if the characters at the start and end positions are equal. If they are equal, 
  -It adds 1 to the start variable and -1 to the end variable ( to check the second wod with the before last one an so on), 
 - If they are not equal, it immediately returns false, indicating that the word is not a palindrome. 
6.	If the loop completes without returning false, it means that the word is a palindrome, and it returns true.
