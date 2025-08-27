## Que. 24: Explain the setTimeout() and setInterval() functions in JavaScript. Howare they used for timing events?

ans. In JavaScript, setTimeout() and setInterval() are functions used to schedule the execution of code at specific times or intervals, which are known as "timing events."

#### setTimeout()

The setTimeout() function is used to execute a function or a piece of code once after a specified delay. 

      setTimeout(function, delayInMilliseconds);

function: The function to be executed after the delay.

delayInMilliseconds: The time, in milliseconds, to wait before executing the function.

Usage for Timing Events: setTimeout() is suitable for tasks that need to occur only once after a set amount of time, such as displaying a "thank you" message after a form submission delay or initiating an animation after a brief pause.

To cancel a setTimeout() call before it executes, the clearTimeout() function is used, passing the ID returned by setTimeout().

#### setInterval()

The setInterval() function is used to execute a function or a piece of code repeatedly at regular intervals. 


        setInterval(function, intervalInMilliseconds);

function: The function to be executed repeatedly.

intervalInMilliseconds: The time, in milliseconds, between each execution of the function. 

Usage for Timing Events: setInterval() is ideal for tasks that require continuous or recurring execution, such as creating a real-time clock, updating a stock ticker, or implementing a slideshow.

To stop the repeated execution of a setInterval() call, the clearInterval() function is used, passing the ID returned by setInterval().