### Learn Python with generative AI
The idea of this portion is that you will be coming up with your own practice questions that are tailored to your level of programming experience.  

Go to ChatGPT, or any other generative AI and type in a prompt like this:

```
I've just completed an entry-level programming course and want to put my 
Python coding skills to practice. 
Can you give me some programming challenge questions at a 
beginner-intermediate level?
```

Here is ChatGPT's response, yours could be different:
```
Of course! Here are some programming challenge questions that are suitable for someone with entry-level programming skills in Python:

**1. Hello, World!**
Write a program that prints "Hello, World!" to the console.

**2. Sum of Numbers**
Write a program that calculates and prints the sum of all numbers from 1 to a given input number.

**3. Factorial Calculator**
Write a program that calculates the factorial of a given number using loops or recursion.

**4. Guess the Number**
Create a simple number guessing game where the program generates a random number and the user tries to guess it. Provide hints such as "higher" or "lower" to help the user guess correctly.

**5. Fibonacci Sequence**
Write a program that generates the first n numbers of the Fibonacci sequence.

**6. Palindrome Checker**
Write a program that checks if a given string is a palindrome (reads the same forwards and backwards).

**7. Prime Number Checker**
Write a program that checks whether a given number is prime or not.

**8. Temperature Converter**
Write a program that converts temperatures between Fahrenheit and Celsius.

**9. Rock, Paper, Scissors**
Create a simple rock-paper-scissors game where the user plays against the computer.

**10. Simple To-Do List**
Build a basic console-based to-do list application that allows the user to add, remove, and list tasks.

**11. Word Count**
Write a program that counts the number of words in a given sentence.

**12. Reverse a String**
Write a program that reverses a given string.

**13. Multiplication Table**
Generate the multiplication table for a given number, up to a specified range.

**14. Pig Latin Translator**
Create a simple Pig Latin translator that converts a given sentence into Pig Latin.

**15. Even and Odd Sum**
Write a program that calculates the sum of even and odd numbers separately within a given range.

**16. Currency Converter**
Build a program that converts between different currencies using predefined exchange rates.

**17. Password Generator**
Write a program that generates a random password with a specified length.

**18. Binary to Decimal Converter**
Create a program that converts a binary number to its decimal equivalent.

**19. Character Frequency Counter**
Write a program that takes a string as input and counts the frequency of each character in the string.

**20. Basic Calculator**
Build a basic calculator that can perform addition, subtraction, multiplication, and division operations.

These challenges cover a range of concepts and skills that will help you solidify your understanding of Python programming. Remember to break down the problems into smaller steps, and don't hesitate to look up documentation or seek help if you get stuck on any particular challenge. Happy coding!
```
Let's pick Pig Latin Translator, we probably want some additional information, so ask the following question:

```
Can you explain the requirements of the "Pig Latin Translator" question? 
And provide me with a sample input and output
```
Here is the response we get:
```
Sure! The Pig Latin Translator is a text transformation program that converts a given sentence or word into Pig Latin. Pig Latin is a playful language game that involves altering the words according to a set of rules.

Here are the basic rules for converting a word into Pig Latin:

1. If a word starts with a consonant (any letter except 'a', 'e', 'i', 'o', 'u'), move the consonant cluster to the end of the word and add "ay". For example, "python" becomes "onpythay".

2. If a word starts with a vowel (any of 'a', 'e', 'i', 'o', 'u'), simply add "way" to the end of the word. For example, "apple" becomes "appleway".

For a sentence, you would apply these rules to each word individually.

Here's a sample input and its expected output:

**Input:** "hello world"
**Output:** "ellohay orldway"

Explanation:
- "hello" starts with a consonant cluster "h" followed by "e". So, we move the consonant cluster "h" to the end and add "ay" to get "ellohay".
- "world" starts with a consonant cluster "w" followed by "o". So, we move the consonant cluster "w" to the end and add "ay" to get "orldway".

Combined, the sentence "hello world" becomes "ellohay orldway" in Pig Latin.

Keep in mind that this is a basic implementation of Pig Latin translation. There are more advanced variations that account for punctuation, capitalization, and other linguistic aspects.
```