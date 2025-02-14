## Que. 2: Explain the concept of CSS specificity. How do conflicts between multiple stylesget resolved?

Ans.CSS specificity refers to a system that determines which style rule takes precedence when multiple styles are applied to the same HTML element, essentially deciding which style "wins" in a conflict by assigning a weight to each selector based on its type (like ID, class, element) - the higher the specificity, the more likely it is to be applied to the element; conflicts between multiple stylesheets are resolved by considering the specificity of each rule, with the rule having the highest specificity taking effect. 

#### Key points about CSS specificity:
##### Specificity hierarchy:

- Inline styles: Highest specificity (applied directly within the HTML element). 
- ID selectors: High specificity (using #id selector). 
- Class selectors: Medium specificity (using .class selector) 
- Element selectors: Low specificity (targeting HTML element tags like `<div>`) 

##### How to calculate specificity:

Each selector is assigned a numerical value based on its type, and the total value determines its specificity. When multiple styles target the same element, the rule with the highest specificity wins. 

##### Resolving conflicts between multiple stylesheets:

- Specificity-based resolution:

When styles from different stylesheets conflict, the rule with the highest specificity will be applied, regardless of which stylesheet it comes from. 
- Order of inclusion:

The order in which stylesheets are linked in the HTML document can also affect which styles are applied. Styles from a stylesheet loaded later can override styles from a stylesheet loaded earlier. 
