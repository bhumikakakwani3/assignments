## Que. 25: Provide an example of how to use setTimeout() to delay an action by 2 seconds.

ans. To delay an action by 2 seconds using setTimeout() in JavaScript, the following example demonstrates the process:


       console.log("Action initiated.");

       // Use setTimeout to delay the execution of a function by 2000 milliseconds (2 seconds)
       setTimeout(() => {
       console.log("This action is delayed by 2 seconds.");
       }, 2000);

      console.log("Further actions can occur immediately after initiating the delayed" );