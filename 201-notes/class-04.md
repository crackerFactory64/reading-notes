## Class 04 - HTML Links, JS Functions, and Intro to CSS Layout

## HTML

### Creating Hyperlinks

Q: To create a basic link, we wrap text or other content inside what element?

A: _a_

Q: The href attribute contains what information?

A: A URL

Q: What are some ways we can ensure links on our pages are accessible to all readers?

A: Ensure the link text is short and semantic. Make it clear that text is a link by following style conventions e.g. underlined, a different colour to regular text.

## CSS Layout

### FLow

In CSS normal flow refers to the default way in which elements are rendered on screen. By default, block elements appear one after each other top to bottom whereas inline elements appear next to each other horizontally.

### Positioning

The default _position_ value for every HTML element is _static_ which means it will follow the default flow. _Absolute_ positioning removes an element from normal flow and allows the developer to manually position an element using the _top_, _right_, _bottom_, and _left_ properties. A similar _position_ value to _absolute_ is _fixed_ but the key difference with _fixed_ is that the position is based on the viewport whereas with _absolute_ it is based on the element's closest ancestor element not in normal flow.

## JS

### Functions – Reusable Blocks of Code

A function is declared, or created, like so:

        function greetUser(name){
                    alert("Welcome, " + name + "!");
                }

To then use, or invoke, that function the developer would type:

        greetUser("Bob");

When invoking a function that uses a parameter, e.g. 'name' in the above example, the value, or argument, is placed in the parentheses after the function name.

## Miscellaneous

### Pair Programming

One benefit to pair programming is the exposure to another developer's coding style and knowledge. This can be benefical as it can introduce someone to new ways of working that improve their programming skills. Another benefit to pair programming is the opportunity it provides to practice interpersonal skills, a useful skill in someone's career and beyond.
