# CSS Layout

## Flexbox

From:[Flexbox](https://web.dev/learn/css/flexbox/)

The Flexible Box Layout Model (flexbox) is a layout model designed for one-dimensional content. It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

They can display as a row, or a column.
They respect the writing mode of the document.
They are single line by default, but can be asked to wrap onto multiple lines.
Items in the layout can be visually reordered, away from their order in the DOM.
Space can be distributed inside the items, so they become bigger and smaller according to the space available in their parent.
Space can be distributed around the items and flex lines in a wrapped layout, using the Box Alignment properties.
The items themselves can be aligned on the cross axis.

The key to understanding flexbox is to understand the concept of a main axis and a cross axis. The main axis is the one set by your flex-direction property. If that is row your main axis is along the row, if it is column your main axis is along the column.

Flex items move as a group on the main axis. Remember: we've got a bunch of things and we are trying to get the best layout for them as a group.

The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.

- Flexbox is designed for one-dimensional content. Explain what this means.

Its good at taking a bunch of items with different sizes and returning the best layout of those items based on the viewport.

- Explain the difference between the main axis and cross axis.

Main axis is like rows and cross axis are like colums.

- How can using certain properties of flexbox negatively impact accessibility?

Because you can change visual order without changing logical order so screen readers will read a order that is not displayed.

## Flexbox2

From: [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

- What are some advantages of using flexbox over float?

Easy verticle alignment, flexible sizing, order control and better handeling of empty space are some advantages to flexbox.

- How does this topic connect with your long term goals?

I am particullary bad at css right now so I need to get better if I want to make visually apealling sites.

## Layout

From: [Layout](https://web.dev/learn/css/layout/)
