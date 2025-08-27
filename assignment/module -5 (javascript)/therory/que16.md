## Que 16: What is an array in JavaScript? How do you declare and initialize an array?
ans. In JavaScript, an array is an ordered list-like structure used to store multiple values in a single variable. Arrays are zero-indexed, meaning the first element is at index 0, the second at index 1, and so on. Array elements can be of any data type, including numbers, strings, booleans, objects, or even other arrays. 

##### Declaring and Initializing an Array:
There are two primary ways to declare and initialize an array in JavaScript:  

###### Array Literal Notation (Recommended): 
This is the most common and concise way to create an array. You use square brackets [] to enclose a comma-separated list of values.

JavaScript

    // Declaring and initializing an array with values
    const fruits = ["apple", "banana", "orange"];

    // Declaring an empty array
    let emptyArray = [];

###### Array Constructor: You can use the Array() constructor to create an array.
 
JavaScript


    // Creating an array with initial values
    const numbers = new Array(1, 2, 3, 4, 5);

    // Creating an array of a specified length (elements will be undefined)
    const fixedLengthArray = new Array(10); // Creates an array with 10 undefined elements