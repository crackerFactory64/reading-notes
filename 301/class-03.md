# Class 03 - Passing Functions as Props

## Lists and Keys

The array method _map()_ returns an array based on the array it is called on, it loops through the original array and performs the provided callback function on each item before returning the modified array. The map() method is useful in React as it can be used to loop through an array of data and return an array of components with each item in the array of data's information passed to them as props. When using this technique each item in the array of components should have a unique _key_ property. Keys are used in React to help track changes to individual components.

## The Spread Operator

The spread operator is denoted by three dots (_..._) and is used to expand iterable data such as arrays or strings and also to access the individual key-value pairs within an object. This can be useful in a number of situations:

### Combining two arrays

When used on arrays the spread operator allows for two or more arrays to be combined into one.

        const array1 = [1, 2];
        const array2 = [3, 4];
        const mergedArray = [...array1, ...array2];
        // mergedArray is [1, 2, 3, 4]

### Adding a new item to an array

The spread operator allows for items to be added to an array conditionally for example:

        const isSummer = false;
        const fruits = ["apple", "banana", ...(isSummer ? ["watermelon"] : [])];
        // ['apple', 'banana']

In this example if _isSummer === true_ then the contents of an array containing the string "watermelon" is added to the fruits array and if not then the contents of an empty array is.

### Creating a copy of an object

The spread operator can be used to create shallow copies of objects.

        const originalObject = { a: 1, b: 2 };
        const copyObject = { ...originalObject };
        // copyObject is a new object with the same properties as originalObject

### Combining two objects into one

The spread operator can combine multiple objects into one, with properties from later objects overwriting properties from earlier objects.

        const obj1 = { a: 1, b: 2 };
        const obj2 = { b: 3, c: 4 };
        const mergedObject = { ...obj1, ...obj2 };
        // mergedObject is { a: 1, b: 3, c: 4 }

## Passing Functions Between Components

[YouTube](https://www.youtube.com/watch?v=c05OL7XbwXU)

In the above video the first step that the developer does to pass functions between components is to create a function within the parent component. The function that is created, _increment()_, contains a .map() call on the _people_ array and loops through it checking each item to see if it's _name_ property matches the one that is supplied via the argument provided when increment is called and if it does increases that object's _count_ property by one. Once it has created a copy of the people array with the change applied it replaces the people array stored in state with that new one.

Functions can be passed from a parent to a child the same way any other form of data can be, via Props. The child component can then use that function by accessing its Props object.
