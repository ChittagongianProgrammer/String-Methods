# String-Methods
Here is an explanation of the code in the two Jupyter notebook files to help create a README file:

## String Indexing.ipynb
This notebook demonstrates string indexing in Python to access elements of a string.

It first shows how to use square brackets [] to access characters in a credit card number string:

- Access first number, last number, slices of numbers
- Skip elements and access every 3rd element
- Slice and print last 4 digits only
- Reverse the string 

It then gets an email address input from user and slices out the username and domain using the index() method to find the @ symbol location.

Key concepts:
- Indexing strings like lists with []
- Slicing strings to get sub-sections 
- Skipping elements 
- Reversing strings
- finding index of characters

## String Methods.ipynb
This notebook covers common Python string methods to manipulate strings.

It gets name and phone number input from user. It then calls various methods:

- len() - get length of string
- find() - find index of character  
- capitalize(), upper(), lower() - change casing
- isdigit(), isalpha() - check if digits or letters 
- count() - count occurrences  
- replace() - replace characters

It shows how these can be used to validate a username, checking length, spaces, and type of characters.

Key concepts:
- String methods like len(), find(), replace() etc
- Manipulating casing and characters
- Checking content with isdigit(), isalpha()
- Validating user input
