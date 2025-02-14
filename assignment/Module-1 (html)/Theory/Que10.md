## Que. 10: Why should tables be used sparingly for layout purposes? What is a better alternative? 

Ans.Tables should be used sparingly for layout purposes because they are not semantically designed for structuring page elements, can be difficult for screen readers to interpret, and can create complex, inflexible layouts; instead, use CSS to style elements within semantic HTML tags like divs, sections, and articles to achieve the desired layout. 

- Key reasons to avoid using tables for layout:

Accessibility issues:
Screen readers struggle to navigate complex table structures, making it hard for visually impaired users to understand the content hierarchy.

Poor semantic meaning:
Using tables for layout doesn't accurately represent the content structure, making it harder for search engines and other applications to understand the page. 

Maintenance complexity:
Complex table layouts can become difficult to modify and maintain as the website evolves. 

- Better alternatives for layout:

CSS Flexbox:
Provides flexible ways to arrange elements in rows and columns without relying on tables.

CSS Grid:
Offers a more structured grid-based layout system for complex page structures. 

Semantic HTML tags:
Using appropriate HTML tags like `<header>`, `<nav>`, `<main>`, `<section>`, and `<article>` to define content sections and then styling them with CSS for visual arrangement. 
