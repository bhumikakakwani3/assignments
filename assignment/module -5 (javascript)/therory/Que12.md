## Que 12: What is the difference between a while loop and a do-while loop in javascript?

ans.The fundamental difference between a while loop and a do-while loop in JavaScript lies in when the loop's condition is evaluated:

##### while loop (Entry-Controlled Loop):
The condition is checked before the code block inside the loop is executed.
If the condition is initially false, the code block will never execute.

Syntax:
JavaScript

        while (condition) {
            // code to be executed
        }

##### do-while loop (Exit-Controlled Loop):
The code block inside the loop is executed at least once before the condition is checked. 
After the first execution, the condition is evaluated. If it's true, the loop continues; otherwise, it terminates.
This guarantees at least one execution of the loop body, even if the condition is initially false.

Syntax:
JavaScript

        do {
            // code to be executed
        } while (condition);

##### In summary:
Use a while loop when you need to execute a block of code only if a certain condition is met from the start (and potentially multiple times).

Use a do-while loop when you need to ensure a block of code executes at least once, and then continues to execute based on a condition.