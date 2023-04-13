# Forms and JS Events

## Web forms — Working with user data

From:[Web forms — Working with user data](https://developer.mozilla.org/en-US/docs/Learn/Forms)

Before starting to code, it's always better to step back and take the time to think about your form. Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

The <label>, <input>, and <textarea> elements
Our contact form is not complex: the data entry portion contains three text fields, each with a corresponding <label>:

The input field for the name is a single-line text field.
The input field for the email is an input of type email: a single-line text field that accepts only email addresses.
The input field for the message is a <textarea>; a multiline text field.

The markup for our form is almost complete; we just need to add a button to allow the user to send, or "submit", their data once they have filled out the form. This is done by using the <button> element; add the following just above the closing </ul> tag:

css for froms: 

form {
  /* Center the form on the page */
  margin: 0 auto;
  width: 400px;
  /* Form outline */
  padding: 1em;
  border: 1px solid #ccc;
  border-radius: 1em;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

form li + li {
  margin-top: 1em;
}

label {
  /* Uniform size & alignment */
  display: inline-block;
  width: 90px;
  text-align: right;
}

input,
textarea {
  /* To make sure that all text fields have the same font settings
     By default, textareas have a monospace font */
  font: 1em sans-serif;

  /* Uniform text field size */
  width: 300px;
  box-sizing: border-box;

  /* Match form field borders */
  border: 1px solid #999;
}

input:focus,
textarea:focus {
  /* Additional highlight for focused elements */
  border-color: #000;
}

textarea {
  /* Align multiline text fields with their labels */
  vertical-align: top;

  /* Provide space to type some text */
  height: 5em;
}

.button {
  /* Align buttons with the text fields */
  padding-left: 90px; /* same size as the label elements */
}

button {
  /* This extra margin represent roughly the same space as the space
     between the labels and their text fields */
  margin-left: 0.5em;
}

The <fieldset> element is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes. You can label a <fieldset> by including a <legend> element just below the opening <fieldset> tag. The text content of the <legend> formally describes the purpose of the <fieldset> it is included inside.

`<li class="button">`
  `<button type="submit">Send your message</button>`
`</li>`

- Why are forms so important in web development?

Forms help collect user data anduser imput.

- When designing a form, what are some key things to keep in mind when it comes to user experience?

Keep it simple and stay focused: ask only for the data you absolutely need.

- List 5 form elements and explain their importance.

1. text imput feilds for users to imput text or numbers

2. Radio buttons to narrow the users imput to less options when specific feeddback is wanted.

3. Check boxes for when multiple options need to be selected from a list.

4. Select menus for making dropdown list selection.

5. Submit button is the final step and sends the data to the server.

## Introduction to events

- How would you describe events to a non-technical friend?

Events are all the interaction things like buttons things popping up. You and the page interact with each other.

- When using the addEventListener() method, what 2 arguments will you need to provide?

The first is the type of event you are looking for the second is a function that occurs when that happenes.

- Describe the event object. Why is the target within the event object useful?

The target property of the event object is always a reference to the element the event occurred upon.

- What is the difference between event bubbling and event capturing?

They go through the elements nested inreverse orders. Bubbeling goes inner to outer and capture goes outter to inner.

From: [Introduction to events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

