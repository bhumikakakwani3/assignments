## que 11: Explain the different types of loops in JavaScript (for, while, do-while). Provide a basic example of each. 
ans. JavaScript provides several types of loops for repetitive execution of code blocks. The three primary types are for, while, and do-while.

#### 1. for loop:
The for loop is used when the number of iterations is known or can be determined before the loop starts. It consists of three optional expressions: initialization, condition, and increment/decrement. 
ex...

     for (let i = 0; i < 5; i++) {
    console.log("For loop iteration:", i);
    }

#### 2. while loop:
The while loop executes a block of code as long as a specified condition evaluates to true. The condition is checked before each iteration. 
ex... 

    let count = 0;
    while (count < 3) {
    console.log("While loop iteration:" ,
      count);
    count++;
    }

#### 3. do-while loop:
The do-while loop is similar to the while loop, but it guarantees that the code block inside the loop will execute at least once, as the condition is checked after the first iteration. 
ex...

    let x = 0;
    do {
    console.log("Do-while 
    loop iteration:", x);
    x++;
    } while (x < 1);
