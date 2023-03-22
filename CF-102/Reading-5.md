# Design web pages with Css

## What is CSS?

From: [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

CSS MAKES YOUR PAGES LOOK NICE!

Specifies how documents are presented to the user

CSS can be used for very basic document text styling — for example, for changing the color and size of headings and links. It can be used to create a layout — for example, turning a single column of text into a layout with a main content area and a sidebar for related information. It can even be used for effects such as animation. Have a look at the links in this paragraph for specific examples.

CSS is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

Ex:

`h1 {
  color: red;
  font-size: 5em;
}`

In this example h1 is the selector choosing which HTML element to style

Inside the braces will be one or more declarations, which take the form of property and value pairs. We specify the property (color in the above example) before the colon, and we specify the value of the property after the colon (red in this example).

## How to add CSS

From [How to add CSS](https://www.w3schools.com/css/css_howto.asp)
There are three ways of inserting a style sheet:

External CSS seperate CSS file

body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}

Internal CSS Inside the HTML code

Inline CSS Inside of HTML element

`<h1 style="color:blue;text-align:center;">This is a heading</h1>`
`<p style="color:red;">This is a paragraph.</p>`

## CSS color Property

From: [CSS color Property](https://www.w3schools.com/cssref/pr_text_color.php)

The color property specifies the color of text.

## Other Reading

[CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

[CSS Tools: Reset CSS](https://meyerweb.com/eric/tools/css/reset/)

[CSS Alminac](https://css-tricks.com/almanac/properties/)

1.What is the purpose of CSS?

-To make the page look pretty, HTML pages can be very boring and CSS gives you visual design control

2.What are the three ways to insert CSS into your project?

-External, Internal and Inline

3.Write an example of a CSS rule that would give all `<p>` elements red text.

-p.ex {
  color: rgb(0,0,255);
}
