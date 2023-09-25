# Class 07 - Object-Orientated Programming, HTML Tables

## Domain modeling

Domain modeling is a way of conceptualising code before writing any which describes the different parts of the script along with their attributes and behaviours. This is important as it allows for technically minded and non-technically minded people to to discuss a problem and the eventual programming solution.

## HTML tables

In HTML tables shouldn't be used for layouts because:

- they reduce accessibilty
- the code required is hard to read
- they are not naturally responsive

Three semantic table elements are:

- th - table header
- tr - table row
- td - table data cell

## Constructors

In JavaScript a constructor is a function that creates a new object , and is called using the _new_ keyword. For instance:

        function Cat(name){
          this.name = name;
          this.meow = function (){
            alert(`My name is ${name}. Meow!`)
          }
        }

        const whisper = new Cat("Whisper");
