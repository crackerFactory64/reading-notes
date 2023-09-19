# Class 03 - Lists, The Box Model, and Loops

## HTML Lists

The two types of list supported by HTML are ordered and unordered lists. Unordered lists are used when the order of list items isn't especially important such as a series of navigation links whereas ordered lists are numbered so are used when providing a step-by-step guide for instance. Unordered lists use bullet points by default but this can be changed with the _list-style-type_ CSS property. Ordered lists can also be modified using the same property and also by using the _type_ attribute within the element tag.

## CSS

Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
List and describe the four parts of an HTML elements box as referred to by the box model.

_Margin_ determines the space between elements and _padding_ determines the space between an element's content and the edge of the element itself.

### Parts of the box model

- Content: the actual content that is displayed on the screen e.g. some text within some _p_ tags
- Padding: the space between the content and the edge of the element
- Border: the edge of the element, usually invisible by default
- Margin: the space between the element and adjacent elements

## JS

### Arrays

Any data types can be stored within an array in javascript. For example the following array would be valid as even other arrays can be stored within an array:

        const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

To access the nested arrays within the 'people' array a developer would use two sets of square brackets for example to log the string containing 'librarian' the following code would be used:

        console.log(people[0][2]);

### Operators and Expressions

#### Top five shorthand assignment operators

- Addition assignment (+=): assigns the variable to the original value plus a second value
- Subtraction assignment (-=): assigns the variable to the original value minus a second value
- Multiplication assignment (\*=): assigns the variable to the original value times a second value
- Division assignment (\=): assigns the variable to the original value divided by a second value
- Remainder assignment (%=): assigns the variable to the remainder of the original value divided by a second value

Q: Read the code below and evaluate the last expression and explain what the result would be and why.

        let a = 10;
                    let b = 'dog';
                    let c = false;

        // evaluate this
                      (a + c) + b;

A: This code return the string '10dog' as adding _false_ to something doesn't add anything and adding a number and a string returns a string.

### Conditionals

Conditionals allow a developer to add logic to some code and have it perform different actions in specific circumstances. For instance the following code would allow or deny a user access to some content depending on their age:

        const age = prompt("How old are you?");

        if (age >= 18){
                  alert("Welcome!")
                } else {
                  alert("Come back when you're 18.")
                }

### Loops

Loops are useful when a developer wants some code to be performed multiple times for example a _for_ loop could be used to print all the strings within an array, like so:

        const staff = ["Tim", "Sam", "Rich"]
                for (let i = 0; i < staff.length; i++){
                  console.log(staff[i])
                }
