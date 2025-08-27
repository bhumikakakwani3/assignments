## Que 17: Explain the methods push(), pop(), shift(), and unshift() used in arrays. 

ans. The methods push(), pop(), shift(), and unshift() are fundamental for manipulating arrays by adding or removing elements. 

###### push(): 
This method adds one or more elements to the end of an array and returns the new length of the array.
JavaScript

    let arr = [1, 2];
    let newLength = arr.push(3, 4); // arr is now [1, 2, 3, 4], newLength is 4

 ###### pop():
 This method removes the last element from an array and returns the removed element. If the array is empty, it returns undefined. 
JavaScript

    let arr = [1, 2, 3];
    let removedElement = arr.pop(); // arr is now [1, 2], removedElement is 3

###### shift():
 This method removes the first element from an array and returns the removed element. It effectively "shifts" all subsequent elements to a lower index. If the array is empty, it returns undefined. 
JavaScript

    let arr = [1, 2, 3];
    let removedElement = arr.shift(); // arr is now [2, 3], removedElement is 1


##### The unshift():
method in JavaScript is used to add one or more elements to the beginning of an array. This method modifies the original array and returns the new length of the array after the elements have been added.

Here's an explanation with code examples:
JavaScript

    // Initial array
    let fruits = ["Banana", "Orange", "Apple"];
    console.log("Original array:", fruits); // Output: Original array: [ 'Banana', 'Orange', 'Apple' ]

     // Adding a single element to the beginning
     let newLength1 = fruits.unshift("Lemon");
    console.log("Array after unshift (single element):", fruits); // Output: Array after unshift (single element): [ 'Lemon', 'Banana', 'Orange', 'Apple' ]
     console.log("New length:", newLength1); // Output: New length: 4

    // Adding multiple elements to the beginning
    let colors = ["Red", "Green"];
    console.log("Original colors array:", colors); // Output: Original colors array: [ 'Red', 'Green' ]

    let newLength2 = colors.unshift("Blue", "Yellow");
     console.log("Array after unshift (multiple elements):", colors); // Output: Array after unshift (multiple elements): [ 'Blue', 'Yellow', 'Red', 'Green' ]
     console.log("New length:", newLength2); // Output: New length: 4

     // Unshift on an empty array
     let emptyArray = [];
     console.log("Original empty array:", emptyArray); // Output: Original empty array: []

    let newLength3 = emptyArray.unshift(10);
    console.log("Array after unshift on empty array:", emptyArray); // Output: Array after unshift on empty array: [ 10 ]
    console.log("New length:", newLength3); // Output: New length: 1