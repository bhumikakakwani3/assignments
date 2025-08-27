## Que 10: Describe how switch statements work in JavaScript. When should you use a switch statement instead of if-else? 

ans.in JavaScript, a switch statement evaluates an expression and then executes a block of code based on matching the expression's value against various case clauses.

##### Here's how it works:
###### Expression Evaluation:
The switch statement takes an expression (e.g., a variable, a function call) and evaluates it once to get a value.

###### Case Comparison:
This evaluated value is then strictly compared (===) with the value specified in each case clause, from top to bottom.
###### Code Execution:
If a match is found, the code block associated with that case is executed. 
###### break Keyword:
The break keyword is crucial. When encountered within a case, it terminates the switch statement, preventing "fall-through" to subsequent case blocks. Without break, execution would continue to the next case's code, regardless of whether it matches.
###### default Keyword:
The optional default clause provides a fallback. If none of the case values match the expression, the code within the default block is executed.
##### When to use switch instead of if-else:

###### Handling Multiple Fixed Values:
Use switch when you need to execute different code blocks based on a single variable or expression having a distinct, fixed set of possible values (e.g., checking days of the week, error codes).
###### Improved Readability for Many Conditions:
When you have a long chain of if-else if-else statements checking for equality against a single variable, a switch statement often makes the code more readable and organized.
###### Performance (in some cases):
For a large number of distinct cases, switch statements can sometimes be optimized by JavaScript engines to perform better than a long if-else if chain due to the potential for jump tables.
###### Clearer Intent:
It explicitly indicates that you are branching based on the value of a single expression.
##### When if-else is more suitable:
###### Complex Conditions:
When you need to check for complex conditions involving relational operators (e.g., greater than, less than), logical operators (AND, OR), or a range of values, if-else is the appropriate choice.
###### Boolean Conditions:
When your branching logic is based on a boolean condition (true/false) rather than discrete values.
###### Variable Conditions:
When the conditions themselves are dynamic or depend on multiple variables.




