## Que 18: What is an object in JavaScript? How are objects different from arrays?
ans. In JavaScript, an object is a non-primitive data type used to store collections of data as key-value pairs. Each key, also known as a property name, is typically a string (or Symbol) and uniquely identifies a value. The value associated with a key can be any data type, including other objects, functions, or primitive values like numbers or strings. Objects are mutable, meaning their properties can be added, modified, or deleted after creation.

##### Here's how objects differ from arrays:

###### Data Access:

Objects: Data is accessed using named keys (property names).
JavaScript

        const person = { name: "Alice", age: 30 };
        console.log(person.name); // Access using dot notation
        console.log(person["age"]); // Access using bracket notation

Arrays:
 Data is accessed using numerical indices, starting from 0.
JavaScript

        const colors = ["red", "green", "blue"];
        console.log(colors[0]); // Access the first element
###### Order:
Objects: The order of properties in an object is not guaranteed to be maintained (though modern JavaScript engines often preserve insertion order for string and Symbol-keyed properties).

Arrays: Elements are stored in a specific, ordered sequence, and their position is defined by their index.

###### Purpose:
Objects: Ideal for representing entities with distinct properties, such as a "person" with a "name" and "age," or a "car" with a "make" and "model."

Arrays: Designed for storing ordered lists or collections of items, where the order of elements is significant, such as a list of "students" or a sequence of "numbers."

###### Structure:
Objects: A collection of named properties, each with a corresponding value.

Arrays: A list of values, each assigned a numerical index.