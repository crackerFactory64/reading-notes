# Class 04 - React and Forms

## Forms

Typically HTML inputs maintain their own value which is set directly by user input but in React, mutable data should be controlled React state. When using inputs within React it is best to have just one source controlling the value. This is done by storing the value which is changed by an input in state, adding an _onChange_ attribute to that input element that updates that value, and then setting the value of the input to the value stored in state. A component made with this technique is called a controlled component.

## The Ternary Operator

In React a ternary operator can be used for conditional rendering, for instance you may have a button for switching between dark and light mode with an icon that changes based on the current state.

        if(x === y){
          console.log(true);
        } else {
          console.log(false);
        }

The previous bit of code can be shortened using a ternary operator like so:

        x === y ? console.log(true) : console.log(false);
