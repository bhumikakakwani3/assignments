## Que 21: How does the addEventListener() method work in JavaScript? Provide an example.

ans.The addEventListener() method in JavaScript is used to attach an event handler to a specified element in the Document Object Model (DOM). This method allows you to set up functions to be called when a specific event occurs on that element, such as a click, mouseover, keydown, or form submission. It is a modern and flexible way to handle events, as it allows multiple event handlers to be attached to the same event type on a single element without overwriting previous handlers. 

###### How it works:
Target Element:
 You first select the HTML element you want to attach the event listener to, typically using methods like document.getElementById(), document.querySelector(), or document.querySelectorAll().

Call addEventListener(): 
You then call the addEventListener() method on the selected element.

Arguments: 
This method takes at least two arguments:

event (string): A string representing the type of event to listen for (e.g., "click", "mouseover", "keydown"). 

function (callback function): The function to be executed when the specified event occurs. This function is often called a "callback" function.

useCapture (boolean, optional): 
An optional third argument that specifies whether the event should be handled during the capturing phase (true) or the bubbling phase (false, default).

###### Example:
This example demonstrates how to use addEventListener() to change the text of a paragraph when a button is clicked.
Code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>addEventListener Example</title>
</head>
<body>
    <button id="myButton">Click me!</button>
    <p id="myParagraph">Initial text.</p>

    <script>
        // Get references to the HTML elements
        const button = document.getElementById('myButton');
        const paragraph = document.getElementById('myParagraph');

        // Define the function to be executed when the button is clicked
        function changeText() {
            paragraph.textContent = 'Text changed by button click!';
        }

        // Attach the event listener to the button
        button.addEventListener('click', changeText);
    </script>
</body>
</html>