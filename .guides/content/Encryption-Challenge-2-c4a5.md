This challenge follow on from challenge 2.1. Copy and paste your code into the code window on the left before you start.

## Introduction
You program converts single plaintext characters into ciphertext but often whole words (and sentences) will need to be encrypted. Your task is to create a program that will encrypt a single word into cipher text.

## Testing
Create a testing table and think of some words that you can encrypt. Use different shifts for each word. A table has been created to help you:

| Test Data          | Expected Output   | Actual Output
| ------------------ | ----------------- | ---------------
| "code" shift 4     | "gshi"            | (add actual output here)

## Need to Know
Read up on For loops and string concatenation before attempting the task.

### For Loop
A `for` loop can be used like this to access each letter in the string:

    word = "school"
    for letter in word:
      print(letter)
      
This would print each letter of the word `school` on a new line. **Try it for yourself**.

### String Concatenation
String concatenation means to join strings together. Here's how to join strings together in Python3:

    word1 = "hello"
    word2 = "hello2"
    words = word1 + word2 //outputs "helloworld"



## Task
 - Allow a user to enter a word
 - For each letter in the word