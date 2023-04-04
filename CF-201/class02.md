# Introduction to HTML

From: [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

At its heart, HTML is a language made up of elements, which can be applied to pieces of text to give them different meaning in a document (Is it a paragraph? Is it a bulleted list? Is it part of a table?), structure a document into logical sections (Does it have a header? Three columns of content? A navigation menu?), and embed content such as images and videos into a page.

Headings help implement structural hierarchy.

## Emphasis and importance

 HTML provides various semantic elements to allow us to mark up textual content with such effects, and in this section, we'll look at a few of the most common ones.

In HTML we use the `<em>` (emphasis) element to mark up such instances. As well as making the document more interesting to read, these are recognized by screen readers, which can be configured to speak them in a different tone of voice. Browsers style this as italic by default, but you shouldn't use this tag purely to get italic styling. To do that, you'd use a `<span>` element and some CSS, or perhaps an `<i>` element (see below).

In HTML we use the `<strong>` (strong importance) element to mark up such instances. As well as making the document more useful, again these are recognized by screen readers, which can be configured to speak them in a different tone of voice. Browsers style this as bold text by default, but you shouldn't use this tag purely to get bold styling. To do that, you'd use a `<span>` element and some CSS, or perhaps a `<b>` element (see below).

### Italic, bold, underline

`<i>` is used to convey a meaning traditionally conveyed by italic: foreign words, taxonomic designation, technical terms, a thought…
`<b>` is used to convey a meaning traditionally conveyed by bold: keywords, product names, lead sentence…
`<u>` is used to convey a meaning traditionally conveyed by underline: proper name, misspelling…

## Advanced text formatting

From: [Advanced text formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

Description lists use a different wrapper than the other list types — `<dl>`; in addition each term is wrapped in a `<dt>` (description term) element, and each description is wrapped in a `<dd>` (description definition) element.

Example:

`<dl>`
  `<dt>soliloquy</dt>`
  `<dd>`
    In drama, where a character speaks to themselves, representing their inner
    thoughts or feelings and in the process relaying them to the audience (but
    not to other characters.)
  `</dd>`
  `<dt>monologue</dt>`
  `<dd>`
    In drama, where a character speaks their thoughts out loud to share them
    with the audience and any other characters present.
  `</dd>`
  `<dt>aside</dt>`
  `<dd>`
    In drama, where a character shares a comment only with the audience for
    humorous or dramatic effect. This is usually a feeling, thought, or piece of
    additional background information.
  `</dd>`
`</dl>`

### Citations

There is a `<cite>`element, but this is meant to contain the title of the resource being quoted, e.g. the name of the book. There is no reason, however, why you couldn't link the text inside `<cite>` to the quote source in some way.

### Superscript and subscript

You will occasionally need to use superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning. The `<sup>` and `<sub>` elements handle this job

`<p>My birthday is on the 25<sup>th</sup> of May 2001.</p>`
`<p>`
  Caffeine's chemical formula is
  `C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>.`
`</p>`
`<p>If x<sup>2</sup> is 9, x must equal 3 or -3.</p>`

### Representing computer code

`<code>`: For marking up generic pieces of computer code.
`<pre>`: For retaining whitespace (generally code blocks) — if you use indentation or excess whitespace inside your text, browsers will ignore it and you will not see it on your rendered page. If you wrap the text in `<pre></pre>` tags however, your whitespace will be rendered identically to how you see it in your text editor.
`<var>`: For specifically marking up variable names.
`<kbd>`: For marking up keyboard (and other types of) input entered into the computer.
`<samp>`: For marking up the output of a computer program.

### Marking up times and dates

`<time datetime="2016-01-20">20 January 2016</time>`

### Abbreviations

Another fairly common element you'll meet when looking around the Web is `<abbr>` — this is used to wrap around an abbreviation or acronym. When including either, provide a full expansion of the term in plain text on first use, along with the `<abbr>` to mark up the abbreviation. This provides a hint to user agents on how to announce/display the content while informing all users what the abbreviation means.

- Why is it important to use semantic elements in our HTML?

Because they help identify what the element does and helps read the code as well as structure the html.d

- How many levels of headings are there in HTML?

There are 6 (h1-h6)

- What are some uses for the `<sup>` and `<sub>` elements?

Adding little nubers and letters like 'th' and CO'2'

- When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?

The full word that is being abbreviated.

## How CSS is structured

From: [How CSS is structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

An external stylesheet contains CSS in a separate file with a .css extension. This is the most common and useful method of bringing CSS to a document. You can link a single CSS file to multiple web pages, styling all of them with the same CSS stylesheet.

An internal stylesheet resides within an HTML document. To create an internal stylesheet, you place CSS inside a `<style> element` contained inside the HTML `<head>`.

- What are ways we can apply CSS to our HTML?

Externally or internally

- Why should we avoid using inline styles?

If a site has multiple pages then a single .css can be applied to all of them

- Review the block of code below and answer the following questions:

- What is representing the selector?

1.h2

- Which components are the CSS declarations?

2.Color and Padding

- Which components are considered properties?

3.Black and 5px

## JavaScript basics

From: [JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

### Operators

An operator is a mathematical symbol that produces a result based on two values (or variables). In the following table, you can see some of the simplest operators, along with some examples to try in the JavaScript console.

### Contitionals

Conditionals are code structures used to test if an expression returns true or not. A very common form of conditionals is the if...else statement. For example:

### Functions

Functions are a way of packaging functionality that you wish to reuse. It's possible to define a body of code as a function that executes when you call the function name in your code. This is a good alternative to repeatedly writing the same code. You have already seen some uses of functions. For example:

These functions, document.querySelector and alert, are built into the browser.

If you see something which looks like a variable name, but it's followed by parentheses— () —it is likely a function. Functions often take arguments: bits of data they need to do their job. Arguments go inside the parentheses, separated by commas if there is more than one argument.

For example, the alert() function makes a pop-up box appear inside the browser window, but we need to give it a string as an argument to tell the function what message to display.

- What data type is a sequence of text enclosed in single quote marks?

A string

- List 4 types of JavaScript operators.

Addition, assignment, Strict equality, not/doesnot equal

- Describe a real world Problem you could solve with a Function.

A math problem could be solved using the right fuction

## Making decisions in your code — conditionals

In any programming language, the code needs to make decisions and carry out actions accordingly depending on different inputs. For example, in a game, if the player's number of lives is 0, then it's game over.

### if...else statements

This code is pretty human-readable — it is saying "if the condition returns true, run code A, else run code B"

the second block of code is not controlled by the conditional statement, so it always runs, regardless of whether the condition returns true or false. This is not necessarily a bad thing, but it might not be what you want — often you want to run one block of code or the other, not both.

### comparison operators

Comparison operators are used to test the conditions inside our conditional statements.

=== and !== — test if one value is identical to, or not identical to, another.
< and > — test if one value is less than or greater than another.
<= and >= — test if one value is less than or equal to, or greater than or equal to, another.

### Logical operators: AND, OR and NOT

If you want to test multiple conditions without writing nested if...else statements, logical operators can help you. When used in conditions, the first two do the following:

&& — AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.
|| — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.

- An if statement checks a __ and if it evaluates to ___, then the code block will execute.

condition true

- What is the use of an else if?

When you want the response to vary depending on the imput

- List 3 different types of comparison operators.

'=== or !==' '< or >' '<= or >='

- What is the difference between the logical operator && and `||`?

With && it makes them both true `||` to make it so all expressions in the chain have to individually evaluate to true
