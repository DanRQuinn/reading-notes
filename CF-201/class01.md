# Class 1 Reading

This reading is important for understanding the basics of web design, HTML, and Java script.

## Getting Started

### How the web works

From: [How the web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

Clients are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).

Servers are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.

### Order in which component files are parsed

When browsers send requests to servers for HTML files, those HTML files often contain `<link>` elements referencing external CSS stylesheets and `<script>` elements referencing external JavaScript scripts. Its important to know the order in which those files are parsed by the browser as the browser loads the page:

- The browser parses the HTML file first, and that leads to the browser recognizing any `<link>`-element references to external CSS stylesheets and any `<script>`-element references to scripts.

- As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.
- The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
- As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

### What will your website look like?

From: [What will your website look like?](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

Planning is the first step

### JavaScript basics

From: [JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

JavaScript is a powerful programming language that can add interactivity to a website. It was invented by Brendan Eich.

JavaScript itself is relatively compact, yet very flexible. Developers have written a variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort. These include:

Browser Application Programming Interfaces (APIs) built into web browsers, providing functionality such as dynamically creating HTML and setting CSS styles; collecting and manipulating a video stream from a user's webcam, or generating 3D graphics and audio samples.
Third-party APIs that allow developers to incorporate functionality in sites from other content providers, such as Twitter or Facebook.
Third-party frameworks and libraries that you can apply to HTML to accelerate the work of building sites and applications.

Variables are containers that store values. You start by declaring a variable with the let keyword, followed by the name you give to the variable:

JavaScript is case sensitive. This means myVariable is not the same as myvariable. If you have problems in your code, check the case!

- Compose a short poem describing how HTTP sends data between computers.

Oh how hard can it be
To communicate with HTTP
If I were a client or server I would see
The text the way it is supposed to be

- Describe how HTML, CSS, and JS files are “parsed” in the browser.

First it parses the HTML file then sends out requests for the .CSS and .JS files then parses them in that order.

- How can you find images to add to a Website?

Look on google or upload your own. Alternatively, copy the image's web address from your browser's address bar for later use.

- How do you create a String vs a Number in JavaScript?

If you put quotes around a number it becomes a string.

- What is a Variable and why are they important in JavaScript?

A variable is a container that stores values. Once declared you can use it in your .JS throughout the document

## Introduction to HTML

From: [Getting started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

### What is HTML?

HyperText Markup Language) is a markup language that tells web browsers how to structure the web pages you visit.

HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of content to make it appear or act in a certain way.

### Anatomy of an HTML element

The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.

The content: This is the content of the element. In this example, it is the paragraph text.

The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

The element is the opening tag, followed by content, followed by the closing tag.

### Nesting elements

Elements can be placed within other elements. This is called nesting. If we wanted to state that our cat is very grumpy, we could wrap the word very in a `<strong>` element, which means that the word is to have strong(er) text formatting:

`<p>My cat is <strong>very</strong> grumpy.</p>`

### Block versus inline elements

A block-level element appears on a new line following the content that precedes it.

Inline elements are contained within block-level elements, and surround only small parts of the document's content (not entire paragraphs or groupings of content).

### Void Elements

Not all elements follow the pattern of an opening tag, content, and a closing tag. Some elements consist of a single tag, which is typically used to insert/embed something in the document.

### Attributes

Attributes contain extra information about the element that won't appear in the content.

An attribute should have:

A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
The attribute name, followed by an equal sign.
An attribute value, wrapped with opening and closing quote marks.

### Boolean Attributes

Sometimes you will see attributes written without values. This is entirely acceptable. These are called Boolean attributes. Boolean attributes can only have one value, which is generally the same as the attribute name. For example, consider the disabled attribute, which you can assign to form input elements.

### Omitting quotes around attribute values

If you look at code for a lot of other sites, you might come across a number of strange markup styles, including attribute values without quotes. This is permitted in certain circumstances, but it can also break your markup in other circumstances.

Always include the attribute quotes.

### Single or double quotes?

In this article you will also notice that the attributes are wrapped in double quotes. However, you might see single quotes in some HTML code. This is a matter of style.

### Anatomy of a HTML document

`<!DOCTYPE html>:` The doctype. When HTML was young (1991-1992), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML. Doctypes used to look something like this:

`<html></html>:`The `<html>` element. This element wraps all the content on the page. It is sometimes known as the root element.

`<head></head>:` The `<head>` element. This element acts as a container for everything you want to include on the HTML page, that isn't the content the page will show to viewers. This includes keywords and a page description that would appear in search results, CSS to style content, character set declarations, and more. You will learn more about this in the next article of the series.

`<meta charset="utf-8">:` The `<meta>` element. This element represents metadata that cannot be represented by other HTML meta-related elements, like `<base>, <link>, <script>, <style> or <title>.` The charset attributes sets the character set for your document to UTF-8, which includes most characters from the vast majority of human written languages. With this setting, the page can now handle any textual content it might contain. There is no reason not to set this, and it can help avoid some problems later.

`<title></title>:` The `<title>` element. This sets the title of the page, which is the title that appears in the browser tab the page is loaded in. The page title is also used to describe the page when it is bookmarked.

`<body></body>:` The `<body>` element. This contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else.

## Document and website structure

From: [Document and website structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

### Basic sections of a document

Header

Navigation bar

Main content

Sidebar

Footer

### HTML for structuring content

In your HTML code, you can mark up sections of content based on their functionality — you can use elements that represent the sections of content described above unambiguously, and assistive technologies like screen readers can recognize those elements and help with tasks like "find the main navigation", or "find the main content."

To implement such semantic mark up, HTML provides dedicated tags that you can use to represent such sections, for example:

header: `<header>`.
navigation bar: `<nav>`.
main content: `<main>`, with various content subsections represented by `<article>`, `<section>`, and `<div>` elements.
sidebar: `<aside>`; often placed inside `<main>`.
footer: `<footer>`.

### HTML layout elements in more detail

`<article>` encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).
`<section>` is similar to `<article>`, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. It's considered best practice to begin each section with a heading; also note that you can break `<article>`s up into different `<section>`s, or `<section>`s up into different `<article>`s, depending on the context.
`<aside>` contains content that is not directly related to the main content but can provide additional information indirectly related to it (glossary entries, author biography, related links, etc.).
`<header>` represents a group of introductory content. If it is a child of `<body>` it defines the global header of a webpage, but if it's a child of an `<article>` or `<section>` it defines a specific header for that section (try not to confuse this with titles and headings).
`<nav>` contains the main navigation functionality for the page. Secondary links, etc., would not go in the navigation.
`<footer>` represents a group of end content for a page.

### Line breaks and horizontal rules

`<br>` creates a line break in a paragraph; it is the only way to force a rigid structure in a situation where you want a series of fixed short lines, such as in a postal address or a poem.

`<hr>` elements create a horizontal rule in the document that denotes a thematic change in the text (such as a change in topic or scene).

### What's in the head? Metadata in HTML

From: [What's in the head? Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

The head of an HTML document is the part that is not displayed in the web browser when the page is loaded. It contains information such as the page `<title>`, links to CSS (if you choose to style your HTML content with CSS), links to custom favicons, and other metadata (data about the HTML, such as the author, and important keywords that describe the document)

- What is an HTML attribute?

Attributes contain extra information about the element that won't appear in the content.

- Describe the Anatomy of an HTMl element.

An opening tag then the content and a closing tag at the end.

- What is the Difference between `<article>` and `<section>` element tags?

An article is used to group content that makes sense on its own while a section is used to group more sparts together that make sense together.

- What Elements does a “typical” website include?

!DOCTYPE, head, title, header, body, main, footer.

- How does metadata influence Search Engine Optimization?

You can put in keywords or languages that help make your website searchable

- How is the `<meta>` HTML tag used when specifying metadata?

It is placed in the head of the document and can be used to specify various types of metadata such as the character encoding, viewport settings, keywords, authorship, ect...

## How do I start to design my website?

From: [How do I start to design my website?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)

A project never starts with the technical side. Musicians will never make any music unless they first have an idea of what they want to play—and the same is true for painters, writers, and web developers. Technique comes second.

Technique is obviously critical. Musicians must master their instrument. But good musicians can never produce good music without an idea. Therefore, before jumping into the technical side — for example, code and tools—you must first step back and decide in detail what you want to do.

An hour's discussion with friends is a good start, but inadequate. You must sit down and structure your ideas to get a clear view of what path you must take to make your ideas a reality. To do this, you need only pen and paper and some time to answer at least the following questions.

- What is the first step to designing a Website?

Doing a deep dive into the subject of the content of the website so you are familiar with the topic.

- What is the most important question to answer when designing a Website?

What exactly do I want to Accomplish

## Semantics

From: [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

In programming, Semantics refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

In JavaScript, consider a function that takes a string parameter, and returns an `<li>` element with that string as its textContent. Would you need to look at the code to understand what the function did if it was called build('Peach'), or createLiWithContent('Peach')?

In CSS, consider styling a list with li elements representing different types of fruits. Would you know what part of the DOM is being selected with div > ul > li, or .fruits__item?

In HTML, for example, the h1 element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

- Why should you use an `<h1>` element over a `<span>` element to display a top level heading?

Because it is more commonly used and easier for other coders to see your intent.

- What are the benefits of using semantic tags in our HTML?

Using semantic tags in HTML can improve the accessibility, SEO, readability, and maintainability of a website.

## What is JavaScript?

From: [What is JavaScript?](https://canvas.instructure.com/courses/6390985/discussion_topics/17584080)

JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which (HTML and CSS) we have covered in much more detail in other parts of the Learning Area.

- Describe 2 things that require JavaScript in the Browser?

It can be used to dynamically update content and control multimedia

- How can you add JavaScript to an HTML document?

By putting it inside of a script tag.
