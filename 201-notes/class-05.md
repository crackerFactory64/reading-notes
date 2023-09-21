# Class 05 - Images, Color, Text

## HTML

### Media

What is a real world use case for the alt attribute being used in a website?
How can you improve accessibility of images in an HTML document?

Images in HTML can be made more accessible with the use of the _alt_ attribute. The _alt_ attribute should contain a description of the image's content that is read aloud by screen readers and displayed on screen in the case of the image failing to load. For example:

        <img src="./tech-ed-logo.jpg" alt="Tech Educators logo" />

The _figure_ element is used to contain an image and optional caption that makes sense on its own such as a graph or map.

### Image formats

An SVG image is different to other image files such as a GIF because it is scalable and won't lose quality at large sizes, this is because an svg file contains a series of instructions to render an image rather than a image itself.

The best image file for a screenshot is a lossless WebP or PNG as it won't lose detail and text remains clear.

## CSS

### Colours

In CSS _background-color_ determines the color of the background of a selected element and simply _color_ defines the color of text and a few other things like borders.

Colour can be used on a web page to give it character. A good way to do this would be to choose a few complimentary colours and apply them to various elements such as headings, paragraphs, buttons, etc.

### Fonts

When choosing a font for a web page it is important to consider font availability. Some fonts are considered web safe fonts and are available on practically every device that is capable of accessing a web page. That doesn't mean that you shouldn't use other fonts but it is important to specify a back-up font such as a web safe font or one of the default fonts such as _serif_. Other than availability font choice should also take into account legibility and suitability for the particular web page it is appearing on e.g. don't use Comic Sans on a memorial page.

Fonts can be modified with the CSS properties _font-size_, _font-weight_, and _font-style_. _Font-size_ determines the size of the text, _font-weight_ affects the thickness of the text, and _font-style_ can be used to make text italic or oblique.

Spacing can be added to text in a element with the _letter-spacing_ and _word-spacing_ properties.

