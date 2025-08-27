 ## Que 20: What are JavaScript events? Explain the role of event listeners.

 ans. JavaScript events are actions or occurrences that happen in the browser, which the system can detect and respond to. These events can be triggered by user interactions (e.g., clicking a button, typing in a text field, moving the mouse) or by the browser itself (e.g., page loading, window resizing).

The role of event listeners is to "listen" for these specific events and, when an event occurs, execute a predefined function or block of code, known as an event handler. Event listeners are crucial for creating interactive and dynamic web pages, as they enable JavaScript to respond to user input and changes in the browser environment.

The addEventListener() method is commonly used to attach an event listener to an HTML element. This method takes the type of event to listen for (e.g., 'click', 'keydown', 'load') and the function to be executed when that event occurs as its arguments. 

For example, to make a button respond to a click:
JavaScript

    const myButton = document.getElementById
    ('myButton');

    myButton.addEventListener
    ('click', function() {
    alert('Button clicked!');
    });
    
In this example, the addEventListener() method is used to attach a 'click' event listener to the element with the ID 'myButton'. When the button is clicked, the anonymous function (the event handler) is executed, displaying an alert message.