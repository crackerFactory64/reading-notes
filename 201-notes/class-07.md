# Class 07 - Object-Oriented Programming, HTML Tables

## Domain modeling

Domain modeling is a way of conceptualising code before actually writing any which describes the different parts of the script along with their attributes and behaviours. This is important as it allows for technically minded and non-technically minded people to to discuss a problem and the eventual solution.

## HTML tables

In HTML tables shouldn't be used for layouts because:

- they reduce accessibility
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

With constructors the _this_ keyword is bound to the new object so it can be used in the creation of the new object.

### Prototypes

Prototype can be used to alter an existing object without redeclaring it, for instance:

        function Cat(name){
          this.name = name;
          this.meow = function (){
            alert(`My name is ${name}. Meow!`)
          }
        }

        Cat.prototype.family = "Felidae"
