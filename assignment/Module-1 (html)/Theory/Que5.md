## Que. 5: What are HTML forms used for? Describe the purpose of the input, textarea,select, and button elements.

Ans.HTML forms are used to collect user input and send it to a server for processing. They are used for a variety of purposes, including user registration, search queries, and feedback submissions. 

- How do HTML forms work?

Users fill out the form by entering data into text fields, selecting radio buttons, or checking checkboxes 

The form data is then sent to a server for processing 

The server can process the data for various purposes, such as updating a user's account or returning search results 




## 1. `<input>`:
- Purpose:
 Used to capture a wide range of user inputs, such as text, numbers, dates, passwords, and more.

- Key Attributes:
type: Specifies the kind of input (e.g., text, password, email, checkbox, radio, etc.).
placeholder: Provides a hint about the expected input.
value: Defines the initial value of the input.

- Example:
`<input type="text" placeholder="Enter your name">`

## 2.` <textarea>`

- Purpose: Designed for capturing multi-line text input, such as comments or messages.
- Key Attributes:
rows and cols: Control the size of the textarea (number of rows and columns).
placeholder: Provides a hint about the expected text.
- Example:
`<textarea rows="4" cols="50" placeholder="Write your comment here"></textarea>`

## 3. `<select>`

- Purpose: Used to create a dropdown menu, allowing users to select one (or multiple) options from a predefined list.
- Key Attributes:
`<option>`: Defines individual items in the dropdown.
multiple: Enables selection of multiple options.
- Example:
`<select>`
  `<option value="apple">Apple</option>`
  `<option value="banana">Banana</option>`
  `<option value="cherry">Cherry</option>`
`</select>`


## 4. `<button>`

- Purpose: Creates a clickable button that can perform actions such as submitting a form, triggering JavaScript functions, or navigating to another page.
- Key Attributes:
type: Specifies the button's behavior (button, submit, reset).
- Example:

`<button type="submit">Submit</button>`

#### Together, these elements make up the building blocks for user interaction in forms and web applications.







