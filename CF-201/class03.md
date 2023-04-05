# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML: HyperText Markup Language

From: [HTML: HyperText Markup Language](https://developer.mozilla.org/en-US/docs/Web/HTML)

### Ordered lists

The `<ol>` HTML element represents an ordered list of items — typically rendered as a numbered list.

reversed
This Boolean attribute specifies that the list's items are in reverse order. Items will be numbered from high to low.

start
An integer to start counting from for the list items. Always an Arabic numeral (1, 2, 3, etc.), even when the numbering type is letters or Roman numerals. For example, to start numbering elements from the letter "d" or the Roman numeral "iv," use start="4".

type
Sets the numbering type:

a for lowercase letters
A for uppercase letters
i for lowercase Roman numerals
I for uppercase Roman numerals
1 for numbers (default)

### The Unordered List element

type Deprecated Non-standard
This attribute sets the bullet style for the list. The values defined under HTML3.2 and the transitional version of HTML 4.0/4.01 are:

circle
disc
square
A fourth bullet type has been defined in the WebTV interface, but not all browsers support it: triangle.

- When should you use an unordered list in your HTML document?

For non numerical listing such as a shopping list or bullet points.

- How do you change the bullet style of unordered list items?

By changing the list type attribute.

- When should you use an ordered list vs an unorder list in your HTML document?

If you were writing step by step instructions.

- Describe two ways you can change the numbers on list items provided by an ordered list?

by changing the type attribute.

## Learn to style HTML using CSS

From: [Learn to style HTML using CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

### Block and inline boxes

In CSS we have several types of boxes that generally fit into the categories of block boxes and inline boxes. The type refers to how the box behaves in terms of page flow and in relation to other boxes on the page. Boxes have an inner display type and an outer display type.

In general, you can set various values for the display type using the display property, which can have various values.

### Outer display type

If a box has an outer display type of block, then:

The box will break onto a new line.
The width and height properties are respected.
Padding, margin and border will cause other elements to be pushed away from the box.
If width is not specified, the box will extend in the inline direction to fill the space available in its container. In most cases, the box will become as wide as its container, filling up 100% of the space available.
Some HTML elements, such as `<h1> and <p>`, use block as their outer display type by default.

If a box has an outer display type of inline, then:

The box will not break onto a new line.
The width and height properties will not apply.
Top and bottom padding, margins, and borders will apply but will not cause other inline boxes to move away from the box.
Left and right padding, margins, and borders will apply and will cause other inline boxes to move away from the box.
Some HTML elements, such as `<a>, <span>, <em> and <strong>` use inline as their outer display type by default.

### Inner display type

 Boxes also have an inner display type, which dictates how elements inside that box are laid out.

Block and inline layout is the default way things behave on the web. By default and without any other instruction, the elements inside a box are also laid out in normal flow and behave as block or inline boxes.

You can change the inner display type for example by setting display: flex;. The element will still use the outer display type block but this changes the inner display type to flex. Any direct children of this box will become flex items and behave according to the Flexbox specification.

When you move on to learn about CSS Layout in more detail, you will encounter flex, and various other inner values that your boxes can have, for example grid.

### CSS box Model

Making up a block box in CSS we have the:

Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
Padding box: The padding sits around the content as white space; size it using padding and related properties.
Border box: The border box wraps the content and any padding; size it using border and related properties.
Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.

- Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Model ordered a box on amazon. But the content was fragile. Padding said we must do something, and continued to surround it with bubble wrap. Padding was worried the box would be too big to fit in the amazon locker, but he checked and the locker was big enough so that there would be room on all sides.

- List and describe the four parts of an HTML elements box as referred to by the box model.

Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
Padding box: The padding sits around the content as white space; size it using padding and related properties.
Border box: The border box wraps the content and any padding; size it using border and related properties.
Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.

## JavaScript — Dynamic client-side scripting

From: [JavaScript — Dynamic client-side scripting](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

### Arrays

Arrays are generally described as "list-like objects"; they are basically single objects that contain multiple values stored in a list. Array objects can be stored in variables and dealt with in much the same way as any other type of value, the difference being that we can access each value inside the list individually, and do super useful and efficient things with the list, like loop through it and do the same thing to every value. Maybe we've got a series of product items and their prices stored in an array, and we want to loop through them all and print them out on an invoice, while totaling all the prices together and printing out the total price at the bottom.

If we didn't have arrays, we'd have to store every item in a separate variable, then call the code that does the printing and adding separately for each item. This would be much longer to write out, less efficient, and more error-prone. If we had 10 items to add to the invoice it would already be annoying, but what about 100 items, or 1000? We'll return to this example later on in the article.

Arrays consist of square brackets and items that are separated by commas.

const shopping = ['bread', 'milk', 'cheese', 'hummus', 'noodles'];
console.log(shopping);

You can find out the length of an array (how many items are in it) in exactly the same way as you find out the length (in characters) of a string — by using the length property. Try the following:

const shopping = ['bread', 'milk', 'cheese', 'hummus', 'noodles'];
console.log(shopping.length);  // 5

### Expressions and operators

At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.

The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7. However, if it's not eventually part of a bigger construct (for example, a variable declaration like const z = 3 + 4), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

`const x = 1 + 2 * 3;`
`const y = 2 * 3 + 1;`

Despite `* and + coming in different orders, both expressions would result in 7 because *` has precedence over +, so the *-joined expression will always be evaluated first. You can override operator precedence by using parentheses (which creates a grouped expression — the basic expression). To see a complete table of operator precedence as well as various caveats, see the Operator Precedence Reference page.

### Making decisions in your code — conditionals

Conditional statements allow us to represent such decision making in JavaScript, from the choice that must be made (for example, "one cookie or two"), to the resulting outcome of those choices (perhaps the outcome of "ate one cookie" might be "still felt hungry", and the outcome of "ate two cookies" might be "felt full, but mom scolded me for eating all the cookies".)

Basic if...else syntax looks like this:

if (condition) {
  `/* code to run if condition is true */`
} else {
  `/* run some other code instead */`
}
Copy to Clipboard
Here we've got:

The keyword if followed by some parentheses.
A condition to test, placed inside the parentheses (typically "is this value bigger than this other value?", or "does this value exist?"). The condition makes use of the comparison operators we discussed in the last module and returns true or false.
A set of curly braces, inside which we have some code — this can be any code we like, and it only runs if the condition returns true.
The keyword else.
Another set of curly braces, inside which we have some more code — this can be any code we like, and it only runs if the condition is not true — or in other words, the condition is false.

### Loops

to make random bubbles appear each time:

for (let i = 0; i < 100; i++) {
  ctx.beginPath();
  ctx.fillStyle = 'rgba(255,0,0,0.5)';
  ctx.arc(random(canvas.width), random(canvas.height), random(50), 0, 2 * Math.PI);
  ctx.fill();
}

- What data types can you store inside of an Array?

Strings, numbers, objects, and even other arrays.

- Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

Yes. if you use myArray you can select individual elements.

- List five shorthand operators for assignment in javascript and describe what they do.

1. Addition assignment

2. Subtraction assignment

3. Multiplication assignment

4. Remainder assignment

5. Left shift assignment

- Read the code below and evaluate the last expression and explain what the result would be and why.

10FalseDog because no numbers are being added it will just connect them all.

- Describe a real world example of when a conditional statement should be used in a JavaScript program.

I someone fails to answer a prompt right then promt again.

- Give an example of when a Loop is useful in JavaScript.

When making the are you a robot images.
