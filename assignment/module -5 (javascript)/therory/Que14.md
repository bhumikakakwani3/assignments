## Que 14: What is the difference between a function declaration and a function expression? 
ans. The difference between a function declaration and a function expression in JavaScript primarily lies in their syntax, hoisting behavior, and how they are defined within the code.

##### Function Declaration:
Syntax: A function declaration is a standalone statement defined using the function keyword, followed by the function name, parameters, and the function body.

JavaScript

    function greet(name) {
      return "Hello, " + name + "!";
    }
###### Hoisting:
 Function declarations are "hoisted" to the top of their scope during the compilation phase. This means they can be called before they are formally declared in the code. 
JavaScript

    console.log(add(5, 3)); // 8
    function add(a, b) {
      return a + b;
    }
##### Function Expression:
Syntax: A function expression defines a function as part of an expression, often assigned to a variable or used as an argument to another function. It can be named or anonymous.

JavaScript

    const multiply = function(a, b) { // Anonymous function expression
      return a * b;
    };

    const subtract = function namedSubtract(a, b) { // Named function expression
      return a - b;
    };

Hoisting: Function expressions are not hoisted in the same way as declarations. They are treated like any other variable assignment, meaning they are only accessible after the line where they are defined has been executed.
JavaScript

    // console.log(divide(10, 2)); // This would result in a ReferenceError
    const divide = function(a, b) {
      return a / b;
    };
    console.log(divide(10, 2)); // 5