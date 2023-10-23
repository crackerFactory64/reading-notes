# Forms and JS Events

## HTML Forms

Forms are important in web development because they provide a simple, user-friendly way for visitors to a web page to interact with a web page by inputting data or controlling a user interface.

When designing a form it is important to consider the user experience (UX). Forms should be concise and focused while making use of the _label_ element to ensure it is clear to all users what each input corresponds to.

Top 5 form elements:

- input- the most common form element allows users to input text
- label- it is important to label form elements so users know what is expected of them
- textarea- better than _input_ for longer text
- select- used to create a dropdown list when the user is required to select from a range of preset answers
- checkbox- allows a user to select one or more preset options

## The event object

The event object is a way for JavaScript to track things that happen on a web page such as a mouse click. The addEventListener is used to check for events within an element or the entire document. The syntax for using this method is:

        const button = document.getElementById("myButton");
        myButton.addEventListener("click", function(){
          alert("The button was clicked");
        })

The method requires an event to check for and a function to perform if that event occurs.

The event object contains a huge amount of properties, one property that is commonly used is the _target_ property. The target property contains data relating to the element where the event occured. With this property we can add interactivity to a web page by modifying an element when a user interacts with it.

_Event bubbling_ is a potentially problematic behaviour whereby an event on a child element also fires on it's parent elements as when, for example, a user clicks on a button within a div they are also technically clicking on that div because it contains the button. The reverse of this is called _event capturing_ where event listeners on child elements are triggered when an event happens on the parent element.
