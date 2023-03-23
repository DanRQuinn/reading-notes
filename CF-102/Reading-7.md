# Programming with JavaScript

## Control flow

From: [Control flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

Looking back at the code in the if and else sections, the lines promptUser and submitForm could also be calls to other functions in the script. As you can see, control structures can dictate complex flows of processing even with only a few lines of code.

## JavaScript Functions

From; [JavaScript Functions](https://www.w3schools.com/js/js_functions.asp)

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

### JavaScript Function Syntax

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
`(parameter1, parameter2, ...)`

Function parameters are listed inside the parentheses () in the function definition.

Function arguments are the values received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.

### Function Invocation

The code inside the function will execute when "something" invokes (calls) the function:

When an event occurs (when a user clicks a button)

When it is invoked (called) from JavaScript code

Automatically (self invoked)

You will learn a lot more about function invocation later in this tutorial.

When JavaScript reaches a return statement, the function will stop executing.

Functions often compute a return value. The return value is "returned" back to the "caller":

Why use functions? You can reuse code: Define the code once, and use it many times.

## JavaScript Operators

The Addition Operator + adds numbers:

The Assignment Operator = assigns a value to a variable.

let x = 10;

let x = 5;
let y = 2;
let z = x + y;

The Multiplication Operator (*) multiplies numbers:

All the comparison operators above can also be used on strings:

`let text1 = "A";`
`let text2 = "B";`
`let result = text1 < text2;`

`== equal to`
`=== equal value and equal type`
`!= not equal`
`!== not equal value or not equal type`
`> greater than`
`< less than`
`>= greater than or equal to`
`<= less than or equal to`
`? ternary operator`

The + can also be used to add (concatenate) strings:

let text1 = "John";
let text2 = "Doe";
let text3 = text1 + " " + text2;

Adding two numbers, will return the sum, but adding a number and a string will return a string:

let x = 5 + 5;
let y = "5" + 5;
let z = "Hello" + 5;

10
55
Hello5

1.What is control flow?

-The control flow is the order in which the computer executes statements in a script.

2.What is a JavaScript function?

-A JavaScript function is a block of code designed to perform a particular task.

3.What does it mean to invoke - or call - a function?

-The code inside the function will execute when "something" invokes (calls) the function:

4.What are the parenthesis () for when you define a function?

-Function parameters
