# Object-Oriented Programming, HTML Tables

## Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

- Explain why we need domain modeling.

to identify and work in a specific problem domain.

From:[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

## HTML table basics

From: [HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data,

HTML tables should be used for tabular data

- Why should tables not be used for page layouts?

the reduce accesibility to the visually impared. It makes "tag soup." Tables are not automatically responsive and wont work effectively across multiple devices.

- List and describe 3 different semantic HTML elements used in an HTML `<table>.`

`<table><tr><td>`

## JavaScript object basics

From: [JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects).

To begin with, make a local copy of our oojs.html file. This contains very little — a `<script>` element for us to write our source code into. We'll use this as a basis for exploring basic object syntax. While working with this example you should have your developer tools JavaScript console open and ready to type in some commands.

- What is a constructor and what are some advantages to using it?

It is object oriented programming that we use to work on class selectors.

- How does the term this differ when used in an object literal versus when used in a constructor?

In an object literal .this refers to the object the is currently being defined. In a constructor, .this refers to the instance of the object being created. It is used to set the properties of the object being created.

## A Beginner's Guide to JavaScript's Prototype

From: [A Beginner's Guide to JavaScript's Prototype](https://ui.dev/beginners-guide-to-javascript-prototype)

Objects are key/value pairs. The most common way to create an object is with curly braces {} and you add properties and methods to an object using dot notation.

let animal = {}
animal.name = 'Leo'
animal.energy = 10

animal.eat = function (amount) {
  console.log(`${this.name} is eating.`)
  this.energy += amount
}

animal.sleep = function (length) {
  console.log(`${this.name} is sleeping.`)
  this.energy += length
}

animal.play = function (length) {
  console.log(`${this.name} is playing.`)
  this.energy -= length
}

- Explain prototypes and inheritance via an analogy from your previous work experience.

If you were making a pizza you have you recipe for the basic cheese this is the prototype. Modifications and topping would be instance. If a customer wanted something similar to one of you recipes but different you could inherit the properties of the previous pizza and make modifications to meet their needs.
