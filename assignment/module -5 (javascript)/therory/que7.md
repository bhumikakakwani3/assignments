## Que7 :What are the different types of operators in JavaScript? Explain with examples. 
#### • Arithmetic operators 
#### • Assignment operators 
#### • Comparison operators 
#### • Logical operators 

Ans. JavaScript provides various types of operators to perform operations on values and variables.

#### Arithmetic Operators
These operators perform mathematical calculations.

ex..
    let a = 10;
    let b = 5;

let sum = a + b; // Addition: 15
let difference = a - b; // Subtraction: 5
let product = a * b; // Multiplication: 50
let quotient = a / b; // Division: 2
let remainder = a % b; // Modulus (remainder of division): 0  

#### Assignment Operators
These operators assign values to variables.
ex..

let x = 10; // Simple assignment

x += 5; // Equivalent to x = x + 5; x is now 15
x -= 3; // Equivalent to x = x - 3; x is now 12
x *= 2; // Equivalent to x = x * 2; x is now 24
x /= 4; // Equivalent to x = x / 4; x is now 6
x %= 2; // Equivalent to x = x % 2; x is now 0

#### Comparison Operators
These operators compare two values and return a boolean (true or false). 
ex..

let p = 10;
let q = 5;

console.log(p == q); // Equal to (loose equality): false
console.log(p === q); // Strict equal to (checks value and type): false
console.log(p != q); // Not equal to (loose inequality): true
console.log(p !== q); // Strict not equal to: true
console.log(p > q); // Greater than: true
console.log(p < q); // Less than: false
console.log(p >= q); // Greater than or equal to: true
console.log(p <= q); // Less than or equal to: false

#### Logical Operators
These operators combine or modify boolean expressions.
ex..

let isAdult = true;
let hasLicense = false;

console.log(isAdult && hasLicense); // Logical AND (true if both are true): false
console.log(isAdult || hasLicense); // Logical OR (true if at least one is true): true
console.log(!isAdult); // Logical NOT (inverts the boolean value): false
