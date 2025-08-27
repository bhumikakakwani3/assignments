## Que 5:  Explain the different data types in JavaScript. Provide examples for each. 
ans. JavaScript has two main categories of data types: Primitive and Non-Primitive (or Reference) data types.

##### 1. Primitive Data Types:
 These represent single, simple values and are immutable (their values cannot be changed after creation).

`String`: Represents textual data. Enclosed in single quotes, double quotes, or backticks.
ex..  
        

    let name = "Alice";
    let greeting = 'Hello!';
    let message = `You are ${name}.`;

`Number`: Represents both integers and floating-point numbers.
ex... 

    let age = 30;
    let price = 19.99;

`Boolean`: Represents logical entities, with only two possible values: true or false.
ex.... 

    let isActive = true;
    let hasPermission = false;

`Undefined`: Represents a variable that has been declared but not yet assigned a value.
ex... 

    let myVariable; // myVariable is
     undefined

`Null`: Represents the intentional absence of any object value. It is a primitive value, not an object.
ex...

    let emptyValue = null;

`Symbol`: Introduced in ES6, Symbols are unique and immutable values often used as object property keys to avoid naming collisions.
ex..

    const id = Symbol('uniqueId');
    const anotherId = Symbol
    ('uniqueId'); // anotherId is
     different from id

`BigInt`: Introduced in ES11, BigInt can represent integers of arbitrary precision, exceeding the limits of the Number type.
ex...

    const largeNumber = 9007199254740991n; 
    // 
    'n' suffix indicates a BigInt




#### 2. Non-Primitive (Reference) Data Types:
 These represent more complex data structures and are mutable (their properties can be changed). They store references to memory locations where the actual data resides.

`Object`: A collection of key-value pairs. Functions and Arrays are specialized types of Objects.
ex.. 

    let person = {
      firstName: "John",
      lastName: "Doe",
      age: 40
    };

`Array`: An ordered list of values, indexed numerically starting from 0. Arrays are a specific type of Object.
ex...

    let colors = 
    ["red", "green", "blue"];        