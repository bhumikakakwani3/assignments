## Que 13: What are functions in JavaScript? Explain the syntax for declaring and calling a function. 

ans. In JavaScript, a function is a reusable block of code designed to perform a specific task. Functions allow for code organization, modularity, and reusability, making programs more efficient and easier to maintain. 

Syntax for Declaring a Function (Function Declaration):
A function declaration begins with the function keyword, followed by the function's name, a set of parentheses () which may contain parameters, and curly braces {} enclosing the function's code block. 

JavaScript

    function functionName
    (parameter1, parameter2) {
    // Code to be executed
     return result; // Optional:
      return a value
      }
###### function:

The keyword indicating a function declaration.

###### functionName:
The name given to the function. This name is used to call the function later.

 ###### parameter1, parameter2:
Optional parameters (or arguments) that the function can accept as input. These are placeholders for values passed into the function when it's called.
###### {}:
The curly braces define the function's body, containing the statements to be executed when the function is called.
###### return result; :
The return statement is optional. If present, it specifies the value the function will output when it finishes execution.

###### Syntax for Calling a Function:
To execute the code within a function, you call it by its name followed by parentheses (). If the function accepts parameters, you pass the corresponding values (arguments) inside the parentheses.

###### JavaScript

functionName(argument1, argument2);    functionName: The name of the function you want to call.
argument1, argument2: The actual values passed to the function's parameters. These values will be used within the function's code block.

###### example:
JavaScript

    // Function Declaration
    function greet(name) {
    console.log("Hello, " + name + "!");
    }

    // Function Call
    greet("Alice"); // Output: Hello, Alice!
    greet("Bob");   // Output: Hello, Bob!