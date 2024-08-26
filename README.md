# ECE2112 Experiment 1

Experiment 1 contains a set of problems for the student to identify the codes and functions in Python Programming and apply them in creating a Python program.

## Alphabet Soup Problem
The problem asks to create a custom or user-defined function that takes in a string and returns the exact string, but its letters are in alphabetical order. This is done by creating a custom function _alphabet_soup(word)_. The functions contain an empty list, the length of the string as variable x, an empty string as variable j, and four for loops. The first for loop modifies the empty list by appending each letter of the word into its own element. The second and third for loops are a nested for loop that sort the letters of the word through a selection sort, which places the smallest element at the beginning of the list. The fourth for loop places each element of the sorted list to variable j and prints each letter of the word, but organized now in alphabetic order.

![image](https://github.com/user-attachments/assets/01ed4d91-e216-442e-ae2e-eed0ae234e53)

## Emoticon Problem
The problem asks to create a custom or user-defined function that replaces a particular word with its corresponding emoticon.

For the word **smile**, its emoticon is **:)**. For the word **grin**, its emoticon is **:D**.

For the word **sad**, its emoticon is **:((**. For the word **mad**, its emoticon is **>:(**.

This is done by creating a tuple containing the abovementioned words, with each word having an assigned index. A custom function with the syntax _emotify(statement)_ is then created, which contains if and elif statements that check if the string contains one of the abovementioned words in the tuple and returns the same string, but the matched word is replaced with its corresponding emoticon.

![image](https://github.com/user-attachments/assets/1e51731b-905b-43cc-b79e-a57111d2f485)


## Unpacking List Problem
The problem asks to unpack a list into three variables: the first element, the last element, and the elements in between the first and last element. This is done by printing the first element with **lst[0]**, which pertains to index 0, which is the first element of the list. The elements between the first and last element are then printed with **lst[1:-1]**, which asks to print the elements starting from index 1 up until before index -1, which is the elements after the first element and before the last element. The last element is last printed with **lst[-1]**, which pertains to index -1, the last element of the list.

![image](https://github.com/user-attachments/assets/26f85291-748a-4db7-a0b5-1bdc30bfbabb)
