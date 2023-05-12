# Putting it all together


## Thinking in React

From[Thinking in React](https://react.dev/learn/thinking-in-react)


- What is the single responsibility principle and how does it apply to components?

The Single Responsibility Principle (SRP) is a principle of software design that states that a software component or module should have only one reason to change. hen applied to components, the SRP means that each component should be responsible for a single task or concern. 

- What does it mean to build a ‘static’ version of your application?

Building a "static" version of an application typically refers to generating a set of HTML, CSS, and JavaScript files that represent the application's user interface without requiring any server-side processing.

- Once you have a static application, what do you need to add?

dynamic functionality.

- What are the three questions you can ask to determine if something is state?

Does it change over time?
Can it be derived from something else?
Does it need to be shared between components?

- How can you identify where state needs to live?

Identify components that use or modify the state, Consider the scope and lifetime of the state, Evaluate the coupling between components

## Higher-Order Functions

From[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

- What is a “higher-order function”?

A higher-order function is a function that takes one or more functions as arguments or returns a function as its result.

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

It takes m and checks to see if it is greater than n and returns true or false.

- Explain how either map or reduce operates, with regards to higher-order functions.

map() is a higher-order function that creates a new array by calling a provided function on each element in the original array. The provided function is a callback function that is executed on each element of the array, and the return value of the function is used to create a new array.
