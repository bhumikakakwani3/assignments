## Que 8: What is the difference between == and === in JavaScript?
ans. In JavaScript, == (loose equality) and === (strict equality) are both used for comparison, but they differ in how they handle data types:

#### == (Loose Equality):
 This operator performs type coercion before comparing values. If the operands have different data types, JavaScript attempts to convert one or both operands to a common type before performing the comparison. This can lead to unexpected results if not used carefully, as values that appear different might evaluate to true due to implicit type conversion.
ex.. 

    console.log(5 == "5"); // true 
    (number 5 is coerced to string "5")
    console.log(true == 1); // true 
    (boolean true is coerced to number 1)

#### === (Strict Equality): 
This operator compares both the value and the data type of the operands without performing any type coercion. For === to return true, both the value and the data type of the operands must be identical. If the data types differ, the comparison will always result in false. 
ex..

    console.log(5 === "5"); // false 
    (different data types: number vs. string)
    console.log(true === 1); // false 
    (different data types: boolean vs. number)
    console.log(5 === 5);   // true
     (same value and same data type)