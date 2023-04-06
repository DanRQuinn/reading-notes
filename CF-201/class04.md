# HTML Links, JS Functions, and Intro to CSS Layout

## Creating hyperlinks

From:[Creating hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

 basic link is created by wrapping the text or other content inside an `<a>` element and using the href attribute, also known as a Hypertext Reference, or target, that contains the web address.

As mentioned before, almost any content can be made into a link, even block-level elements. If you want to make a heading element a link then wrap it in an anchor (`<a>`) element as shown in the following code snippet:

`<a href="https://developer.mozilla.org/en-US/">`
  `<h1>MDN Web Docs</h1>`
`</a>`
`<p>Documenting web technologies, including CSS, HTML, and JavaScript, since 2005.</p>`

If you have an image you want to make into a link, use the `<a>` element to wrap the image file referenced with the `<img>` element.

`<a href="https://developer.mozilla.org/en-US/">`
  `<img src="mdn_logo.svg" alt="MDN Web Docs homepage" />`
`</a>`

- To create a basic link, we wrap text or other content inside what element?

It is wrapped in a `<a>` elememt wit href attribute.

- The href attribute contains what information?

Thr href contains the URL or web adress.

- What are some ways we can ensure links on our pages are accessible to all readers?

Add supporting information like a title, use key words that make the link make sense.

## CSS layout

From: [CSS layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)

### Normal Flow

By default, a block level element's content fills the available inline space of the parent element containing it and the element grows along the block dimension to accommodate its content. The size of inline elements is just the size of their content. You can't set width or height on inline elements — they just sit inside the content of block level elements — except for images


### Positioning

Positioning allows you to take elements out of normal document flow and make them behave differently, for example, by sitting on top of one another or by always remaining in the same place inside the browser viewport.

Static positioning is the default that every element gets. It just means "put the element into its normal position in the document flow — nothing special to see here."

Relative positioning is the first position type we'll take a look at. This is very similar to static positioning, except that once the positioned element has taken its place in the normal flow, you can then modify its final position, including making it overlap other elements on the page. 

top, bottom, left, and right are used alongside position to specify exactly where to move the positioned element to. To try this out, add the following declarations to the .positioned rule in your CSS:



- What is meant by “normal flow”?

The way the HTML lays out the content.

- What are a few differences between block-level and inline elements?

The block-level elements effect the availible space of the parent element containing it while the inline element is just the size of the content.

- ___ positioning is the default for every html element.

Static.

- Name a few advantages to using absolute positioning on an element.

Because it will no longer be pushed around by other elements on the page.

- What is a key difference between fixed positioning and absolute positioning?

Absolute places an element in regards to its nearest ancestor, Fixed bases it off of the Page.

## Functions — reusable blocks of code

From: [Functions — reusable blocks of code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

Another essential concept in coding is functions, which allow you to store a piece of code that does a single task inside a defined block, and then call that code whenever you need it using a single short command — rather than having to type out the same code multiple times.

Some functions require parameters to be specified when you are invoking them — these are values that need to be included inside the function parentheses, which it needs to do its job properly.

Parameters are sometimes called arguments, properties, or even attributes.

scope — a very important concept when dealing with functions. When you create a function, the variables and other things defined inside the function are inside their own separate scope, meaning that they are locked away in their own separate compartments, unreachable from code outside the functions.

- Describe the difference between a function declaration and a function invocation.

The declaratio  is when the function is made, invocation is when it is used.

- What is the difference between a parameter and an argument?

A paramater is like a variable inside the function.
