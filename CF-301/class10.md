# In memory storage

## The JavaScript Call Stack - What It Is and Why It's Necessary

From[The JavaScript Call Stack - What It Is and Why It's Necessary](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

- What is a ‘call’?

It is a function invocation

- How many ‘calls’ can happen at once?

JavaScript is a single-threaded language, which means that only one thread can be executing code at a time. 

- What does LIFO mean?

Last In, First Out

- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

main()
    func1()
        func2()
            func3()

- What causes a Stack Overflow?

 stack overflow is a type of error that occurs when a program tries to use more memory than is available on the call stack

## JavaScript error messages && debugging

From[JavaScript error messages && debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

- What is a ‘reference error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

- What is a ‘syntax error’?

this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

- What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

- What is a ‘type error’?

types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

- What is a breakpoint?


A breakpoint is a line of code in a program that causes the debugger to stop execution.

- What does the word ‘debugger’ do in your code?

The word "debugger" in my code is a keyword that tells the debugger to stop execution at that point.

## Bookmarks

[JavaScript error reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
