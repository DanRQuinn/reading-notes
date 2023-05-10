# Passing Functions as Props

## Lists and Keys

From: [Lists and Keys](https://legacy.reactjs.org/docs/lists-and-keys.html)




- What does .map() return?

An Array with elements changed by a called function

- If I want to loop through an array and display each value in JSX, how do I do that in React?



- Each list item needs a unique ____.

ID.

- What is the purpose of a key?

It is a special attribute that is used to identify each element in a list of components or elements

## How to Use the Spread Operator (…) in JavaScript

From: [How to Use the Spread Operator (…) in JavaScript](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)




- What is the spread operator?

The spread operator in JavaScript is denoted by three consecutive dots ... and is used to expand or spread the contents of an iterable, such as an array or an object.

- List 4 things that the spread operator can do.

1. Copying an array
2. Concatenating or combining arrays
3. Using Math functions
4. Using an array as arguments

- Give an example of using the spread operator to combine two arrays.

`
const array1 = [1, 2, 3];
const array2 = [4, 5, 6];

const combinedArray = [...array1, ...array2];

console.log(combinedArray); // Output: [1, 2, 3, 4, 5, 6]
`

- Give an example of using the spread operator to add a new item to an array.

`
const myArray = [1, 2, 3];

const newArray = [...myArray, 4];

console.log(newArray); // Output: [1, 2, 3, 4]
`
- Give an example of using the spread operator to combine two objects into one.

`
const object1 = { a: 1, b: 2 };
const object2 = { c: 3, d: 4 };

const combinedObject = { ...object1, ...object2 };

console.log(combinedObject); // Output: { a: 1, b: 2, c: 3, d: 4 }

`
## React - How to Pass Functions between Components - Episode 22

From: [React - How to Pass Functions between Components - Episode 22](https://www.youtube.com/watch?v=c05OL7XbwXU)




- In the video, what is the first step that the developer does to pass functions between components?

He creates the function where he wants the state to change.

- In your own words, what does the increment function do?

It increases a variable by an amount that is determined by your function.

- How can you pass a method from a parent component into a child component?

You can define the method in the parent component and then pass it down to the child component as a prop.

- How does the child component invoke a method that was passed to it from a parent component?

The child component can simply call the method using the prop that was passed down to it

## Bookmark and Review

[Tutorial: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)

[Lifting State Up](https://legacy.reactjs.org/docs/lifting-state-up.html)
