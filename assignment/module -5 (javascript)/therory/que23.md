## Que. 23: Explain the methods getElementById(), getElementsByClassName(),and querySelector() used to select elements from the DOM.

ans. The methods getElementById(), getElementsByClassName(), and querySelector() are used in JavaScript to select elements from the Document Object Model (DOM) for manipulation or interaction.

#### document.getElementById(id):

This method is used to select a single HTML element based on its unique id attribute.
It returns the Element object corresponding to the specified ID.
If no element with the given ID exists, it returns null.

Example:


        const myElement = document.getElementById('uniqueId');


#### document.getElementsByClassName(className):

This method is used to select all HTML elements that have a specific class attribute.
It returns a live HTMLCollection of elements. This collection is "live" meaning it automatically updates if elements are added or removed from the DOM that match the specified class.

Example:


        const elementsWithClass = document.getElementsByClassName('highlight');

#### document.querySelector(selector):

This method is used to select the first HTML element that matches a specified CSS selector.
It can select elements by ID (#id), class (.class), tag name (tagName), or any combination of CSS selectors.
It returns the first Element object matching the selector, or null if no match is found.

Example:


        const firstDiv = document.querySelector('div');
        const specificElement = document.querySelector('#header .title');
