 ## Que 2: Describe the grid-template-columns, grid-template-rows, and grid-gap properties. Provide examples of how to use them.

 Ans.
 ### "grid-template-columns":
 The grid-template-columns property in CSS specifies the number and width of columns in a grid layout. It's used in CSS Grid Layout to define the columns' size, shape, and position. 

 #### example:
 .grid-container {

  display: grid;

  grid-template-columns: 200px 1fr 100px;

}
### "grid-template-rows":
"Grid-template-rows" is a CSS property used to define the size and number of rows within a grid layout, allowing you to specify the height of each row individually using values like pixels, percentages, or the "fr" unit for flexible sizing; essentially, it controls how the vertical space in a grid container is divided up between its rows. 


#### example:
.grid-container {

  display: grid;

  grid-template-rows: 100px 200px 1fr; 

}

### "grid-gap-property":
ou can define the space between rows and columns using grid-gap, like this: `grid-gap`: 20px 30px; , which sets 20px `row gaps` and 30px `column gaps`.
