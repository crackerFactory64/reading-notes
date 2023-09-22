# Class 06 - Objects and the DOM

## JavaScript Object Basics

In JavaScript, objects are a collection of related information and processes, sort of like how a passport in real life contains several pieces of information related to a person and also provides the means to enter a country. When an object is defined 'by hand' it is known as an object literal. Advantages to using objects include:

- when transferring data, objects are more efficient than sending individual pieces of data
- objects are easier to work with than arrays because the way in which data within an object is typically accessed, dot notation, is clearer to interpret by people than array index accessing

Although dot notation is easier to read than bracket notation, bracket notation can still be used to access data within an object and is necessary when accessing data based on an expression rather than a manually typed identifier.

In objects, the keyword _this_ refers to the object itself. In the following example, thanks to _this_, the humanAge function uses information within the same object it is a part of to perform a mathematical operation and log a string to the console.

        const dog = {
          name: 'Spot',
          age: 2,
          color: 'white with black spots',
          humanAge: function (){
          console.log(`${this.name} is ${this.age*7} in human years`);
          }
        }

## Introduction to the DOM

The DOM, or Document Object Model, provides an interface between a HTML document and a programming language such as JavaScript. It models the web elements as a series of objects and nodes(connections), rendering the page in a way that the programming language understands and allowing those elements to be accesed and modified through code. In JavaScript this allows developers to add interactivity and dynamic elements to web pages in a controlled way.
