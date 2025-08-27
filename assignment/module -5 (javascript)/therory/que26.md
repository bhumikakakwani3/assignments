## Que. 26: What is error handling in JavaScript? Explain the try, catch, and finally blocks with an example.

ans. Error handling in JavaScript refers to the process of anticipating, detecting, and responding to errors or exceptions that occur during the execution of a program. It allows developers to prevent crashes, provide informative feedback to users, and maintain the stability and robustness of applications.

##### The try...catch...finally construct is a fundamental mechanism for error handling in JavaScript:

try block:
This block contains the code that is to be tested for errors. If an error occurs within the try block, the execution of the try block is immediately stopped, and control is transferred to the catch block.

catch block:
This block is executed only if an error occurs in the try block. It receives an Error object as an argument, which contains information about the error (e.g., name, message). This block is used to handle the error gracefully, such as logging the error, displaying an error message to the user, or attempting to recover from the error.

finally block:
This block is optional and executes after both the try and catch blocks, regardless of whether an error occurred or not. It is typically used for cleanup operations, such as closing files, releasing resources, or resetting variables, ensuring that these actions are performed even if an error disrupts the normal flow of execution. 

Example:


     function divideNumbers(a, b) {
     try {
     if (b === 0) {
      throw new Error("Cannot divide by zero."); // Custom error thrown
    }
     const result = a / b;
     console.log("Division result:", result);
    } catch (error) {
    console.error("An error occurred:", error.message); // Handling the error
    } finally {
    console.log("Division attempt complete."); // Always executes
     }
    }

     divideNumbers(10, 2);   // No error, 'try' and 'finally' execute
     divideNumbers(5, 0);    // Error, 'try', 'catch', and 'finally' execute