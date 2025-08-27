## Que. 22: What is the DOM (Document Object Model) in JavaScript? How does JavaScript interact with the DOM?
  
  
ans. The Document Object Model (DOM) is a programming interface for web documents. It represents the structure of a webpage as a tree of objects, where each object corresponds to a part of the webpage, such as elements (e.g., `<div>`, `<p>`), attributes (e.g., id, class), and text content. The DOM provides a standardized way for programs to access, manipulate, and update a webpage's content, structure, and style dynamically. 

JavaScript interacts with the DOM by using its methods and properties to:

###### Select Elements: JavaScript can select specific elements within the DOM using methods like getElementById(), getElementsByClassName(), querySelector(), and querySelectorAll()


    const myDiv = document.getElementById('myId');
    const paragraphs =
     document.getElementsByClassName('myClass');
    const firstParagraph =
     document.querySelector('p');
    const allLinks = document.querySelectorAll('a');

###### Modify Content: JavaScript can change the text content or HTML structure of elements using properties like textContent or innerHTML.


    myDiv.textContent = 'New text content';
    firstParagraph.innerHTML = 
    '<em>New</em> HTML content';


###### Change Styles and Attributes: JavaScript can modify the CSS styles of elements using the style property or change HTML attributes using methods like setAttribute() and removeAttribute().


    myDiv.style.color = 'blue';
    firstParagraph.setAttribute('data-info', 'some-value');


###### Add and Remove Elements: JavaScript can create new elements using createElement() and add them to the DOM using methods like appendChild() or insertBefore(). It can also remove elements using remove().


    const newElement = document.createElement('span');
    myDiv.appendChild(newElement);
    firstParagraph.remove();


###### Handle Events: JavaScript can attach event listeners to DOM elements to react to user interactions (e.g., clicks, key presses) using addEventListener().


    const myButton = document.getElementById('myButton');
    myButton.addEventListener('click', () => {
        alert('Button clicked!');
    });
    
Through these interactions, JavaScript enables dynamic and interactive web experiences, allowing web pages to respond to user input and update their content without requiring a full page reload.
    