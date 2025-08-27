## Que 6: What is the difference between undefined and null in JavaScript? 
ans. In JavaScript, both undefined and null signify the absence of a meaningful value, but they represent different types of absence and are used in distinct contexts:

### `undefined`: 
###### Implicit Absence:
undefined indicates that a variable has been declared but has not been assigned a value. It is the default value for uninitialized variables.

###### Non-existent Properties:
When attempting to access a property of an object that does not exist, the result is undefined.

###### Function Return:
If a function does not explicitly return a value, it implicitly returns undefined.

###### Type:
The typeof operator returns 'undefined' for undefined.

### `null`:

###### Explicit Absence:
null is an assignment value that represents the intentional absence of any object value. It must be explicitly assigned to a variable.

###### Intentional Empty State:
It is used when a variable or object is meant to have no value, often to indicate that a reference points to nothing.

###### Type:
The typeof operator returns `'object'` for null, which is a historical quirk in JavaScript.