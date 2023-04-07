# Images, Color, Text

## HTML Media

From:[Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)

### Images in HTML

In order to put a simple image on a web page, we use the `<img>` element. This is a void element (meaning, it cannot have any child content and cannot have an end tag) that requires two attributes to be useful: src and alt. The src attribute contains a URL pointing to the image you want to embed in the page. As with the href attribute for `<a>` elements, the src attribute can be a relative URL or an absolute URL. Without a src attribute, an img element has no image to load.

You can use the width and height attributes to specify the width and height of your image. You can find your image's width and height in a number of ways. For example on the Mac you can use Cmd + I to get the info display up for the image file.

`<img`
  src="images/dinosaur.jpg"
  alt="The head and torso of a dinosaur skeleton;
          it has a large head with long sharp teeth"
  width="400"
  height="341" />`

## Image file type and format guide

- What is a real world use case for the alt attribute being used in a website?

For someone who is using a screen reader you could describe the image.

- How can you improve accessibility of images in an HTML document?

BY putting in alt tags and compressing you img file size. You can also put a `<p>` tag with a img description

- Provide an example of when the figure element would be useful in an HTML document.

I you wanted the `<p>` tag to be associated with a img to improve accessibility.

- Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.

A git image is defined by its pixels and if you were to change the ratio the img could become stretched or smooshed. vector graphis retain their porportions and ratio so they can be changed to different sizes with ease.

- What image type would you use to display a screenshot on your website and why?

PNG because it preserves image quality, transparency and has a small file size.

## Learn to style HTML using CSS

From: [Learn to style HTML using CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

### Applying color to HTML elements using CSS

The use of color is a fundamental form of human expression. Children experiment with color before they even have the manual dexterity to draw. Maybe that's why color is one of the first things people often want to experiment with when learning to develop websites. With CSS, there are lots of ways to add color to your HTML elements to create just the look you want.

At a fundamental level, the color property defines the foreground color of an HTML element's content and the background-color property defines the element's background color. These can be used on just about any element.

#### Text

color
The color to use when drawing the text and any text decorations (such as the addition of under- or overlines, strike-through lines, and so forth.

background-color
The text's background color.

text-shadow
Configures a shadow effect to apply to text. Among the options for the shadow is the shadow's base color (which is then blurred and blended with the background based on the other parameters). See Text drop shadows to learn more.

text-decoration-color
By default, text decorations (such as underlines, strikethroughs, etc.) use the color property as their colors. However, you can override that behavior and use a different color for them with the text-decoration-color property.

text-emphasis-color
The color to use when drawing emphasis symbols adjacent to each character in the text. This is used primarily when drawing text for East Asian languages.

caret-color
The color to use when drawing the caret (sometimes referred to as the text input cursor) within the element. This is only useful in elements that are editable, such as `<input> and <textarea>` or elements whose HTML contenteditable attribute is set.

#### boxes

- Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

The foreground its the main parts of the element and the background is what fills the space behing it.

- Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

I might use it to hightlight text and make borders for boxes and sections. I would also choose a pleasing background color that doesnt distract from the forground

- What should you consider when choosing fonts for an HTML document?

Is it readable and web safe.

- What do font-size, font-weight, and font-style do to HTML text elements?

  `font-size` changes the size of the font
  `font-weight` sets the boldness of the font
  `lighter`, `bolder`; sets the current elements boldness to be one step lighter or heavier than its parent element's boldness.

- Describe two ways you could add spacing around the characters displayed in an h1 element.

Padding and Margin.
