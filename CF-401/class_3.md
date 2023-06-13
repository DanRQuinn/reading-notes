# FileIO & Exceptions

## Read & Write Files in Python

From: [Read & Write Files in Python](https://realpython.com/read-write-files-python/)

This article talks about various ways to read and write files in python. It is important because we need to be able to navigate our file structure properly.

## Exceptions in Python

From: [Exceptions in Python](https://realpython.com/python-exceptions/)

This article talks about exeptions. Exceptions are basically error catches. If the syntax is right but the code errors out thats an exception.

## File Objects - Reading and Writing to Files

From: [File Objects - Reading and Writing to Files](https://www.youtube.com/watch?v=Uh2ebFW8OYM)

This video went over some things from the last reading and reiderates open read() readline() and talks about tell and seek.

## Questions

- What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?

It closes the file once it finishes the with code block. With statments write reliable readable and concise code.

- Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.

read() takes in awhole document wheras readline() grabs a single line of code. When It reads them it temporarily stores it in memory. read() would be good for reading a document. readline() can be usefull in situations where you need to grab a snipet from a doc.

- Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

This is a three step process to make sure your site doesn't crash If try doesn't work there is a catch that runs and if all else fails fillany is a catch all.

If you wanted the user to enter a number the execpt might be asking the user to enter a number instead of a string. The finally might be a message letting the user know they inputed the correct information.

## Reading and links

[Reading and Writing Files in Python Quiz](https://realpython.com/quizzes/read-write-files-python/)
