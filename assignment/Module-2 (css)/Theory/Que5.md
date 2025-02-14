## Que. 5: What is the difference between `border-box` and `content-box` box-sizing in CSS? Which is the default?

Ans.In CSS, "border-box" box-sizing means that the specified width and height of an element include any padding and border, while "content-box" (the default) only refers to the content area, with padding and border added on top of that specified width and height, making the element appear larger than intended if padding and border are added. 

###### Key points:
- "border-box":
When using "border-box", the declared width and height of an element will encompass the content, padding, and border, ensuring the element stays within the specified size.
- "content-box":
With "content-box", the declared width and height only refer to the content area, and any padding or border added will increase the overall size of the element beyond the specified dimensions. 


###### Default behavior: 
- The default box-sizing in CSS is "content-box". 


###### When to use "border-box":
- When you want to precisely control the total size of an element, including padding and border. 
- When creating consistent layouts where elements should not unexpectedly expand due to added padding or borders. 
