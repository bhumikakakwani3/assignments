## Que. 1: What is a CSS selector? Provide examples of element, class, and ID selectors.

Ans.A CSS selector is the first part of a CSS Rule. It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them.


- Element Selector:
p { color: blue; } - This will style all paragraph (`<p>`) elements on the page with blue text.

- Class Selector:
.highlight { background-color: yellow; } - This will style any element with the class "highlight" with a yellow background color.

- ID Selector:
#header { font-size: 24px; } - This will style the element with the ID "header" with a font size of 24 pixels. 


##### Explanation:
- Element selectors
target elements based on their HTML tag name, like "p" for paragraph or "h1" for heading 1. 
- Class selectors
target elements with a specific class attribute, denoted by a period (".") followed by the class name. 
- ID selectors
target a single unique element on a page using its ID attribute, indicated by a hash symbol ("#") followed by the ID name. 

##### Key points to remember:

- An element can have multiple classes, but only one ID. 
- Use ID selectors sparingly for specific elements that need unique styling. 
- Class selectors are generally preferred for styling groups of similar elements. 