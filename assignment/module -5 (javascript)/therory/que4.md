## Que4 : What are variables in JavaScript? How do you declare a variable using var, let, and const? 
ans. In JavaScript, variables are named containers used to store data values. They allow you to hold and manipulate different types of information within your program, such as numbers, text (strings), or more complex data structures like objects and arrays. 

Variables in JavaScript can be declared using the keywords `var`, `let`, and `const`, each with distinct characteristics regarding scope, hoisting, and re-assignment:

#### `var` :

Declaration: `var variableName`; or `var variableName = value`;

Scope : var variables are function-scoped or globally-scoped. This means they are accessible throughout the entire function in which they are declared, or globally if declared outside any function.

Hoisting : var declarations are hoisted, meaning they are moved to the top of their containing scope during compilation. This allows you to use a var variable before its declaration in the code, though its value will be undefined until the actual assignment.

Re-assignment and Re-declaration : var variables can be re-assigned and re-declared within the same scope.


#### `let`:
Declaration: `let variableName`; or `let variableName = value`;

Scope : `let` variables are block-scoped. They are only accessible within the block (e.g., if statements, for loops, or any code enclosed in curly braces {}) where they are declared.

Hoisting : `let` declarations are hoisted, but they are not initialized until their declaration is encountered in the code. This creates a "temporal dead zone" where attempting to access a let variable before its declaration will result in a ReferenceError. 

Re-assignment and Re-declaration : `let` variables can be re-assigned within their scope, but they cannot be re-declared within the same block scope.


#### `const` :

Declaration : `const variableName = value`; (must be initialized at declaration)

Scope : const variables are block-scoped, similar to let.

Hoisting: `const` de clarations are hoisted but are also in a temporal dead zone, requiring initialization at the point of declaration.

Re-assignment and Re-declaration : `const` variables cannot be re-assigned or re-declared after their initial assignment. However, if a const variable holds an object or array, the contents of that object or array can still be modified.