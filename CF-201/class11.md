# Audio, Video, Images

## Video and audio content

From:[Video and audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

The `<video>` element allows you to embed a video very easily. A really simple example looks like this:

`<video src="rabbit320.webm" controls>`
  `<p>`
    Your browser doesn't support HTML video. Here is a
    <`a href="rabbit320.webm">link to the video</a>`instead.
  `</p>`
`</video>`

- Explain how the ability to use video and audio on the web has evolved since the early 2000s.

We used to have plugins such as Flash player to get video to work. Now You can embed it in the html.

- Describe the use of the src and controls attributes in the `<video>` element.

Src is the same as we see it with img files, it contains the path to the video. The controls are a bit more complicated you can use some that are built in to the browser or build your own but you need a start and stop button as well as volume control.


- Why is it important to have fallback content inside the <video> element?

In case the user has an older browser. There wil still be a way to play the video.

- Write a very short story where `<audio> and <video>` are characters.

Rockstars `<audio>` and `<video>` were about to do a stage dive. `<video>` looks over to `<audio>` fear on his face. "i hope they can support me!"

## A Complete Guide to CSS Grid

From: [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

- How does Grid layout differ from Flex?

It is 2 dimentional, but they do work very well together because they have different uses.

- Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

Grid container is the box that yyou make the grid with. Grid lines are rows and coloums in the grid. and items are what sits on those rows and coloums and are direct children of the caontainer.

## Responsive Images

From: [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

- Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

So that Images don't get cut off and are appropriatly sized.

- Define the following` <img> `attributes srcset and sizes. Write an example of how they are used.

 They are used to have a selection of different sized images. this is so different images will be used depending on the size of the device.

- How is srcset more helpful for responsive images than CSS or JavaScript?

Because you don't have to work out the correctly sized image the browser will do it for you.
