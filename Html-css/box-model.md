# CSS Box Model 

Each HTML element behaves like a box that has the following properties:

- content width
- content height
- padding (top, bottom, left, right)
- border (top, bottom, left, right)
- margin (top, bottom, left, right)

These properties can be changed using CSS. Changing any one of those properties affects how the box appears on the page, and how that element interacts with the other elements around it.

The box model is not the only thing that can change the look of an HTML element. Every element also has a display property that defines how it stacks with the other elements, e.g., horizontally, vertically, hidden, etc. that can affect its appearance.

## Why is box model important
Understanding the box model and what properties can change the appearance of an HTML element can enable you to style HTML elements with CSS quickly and easily without having to attempt trial-and-error changes.

If trial-and-error does become necessary, it can be done using the browser's developer tools that make it easier to visualize the relationship between different HTML elements. The developer tools allow the developer to make rapid changes to the HTML and CSS running in the browser to see what those changes would look like immediately. This allows the developer to narrow down the problem much more quickly than is possible in a typical development environment where code files need to be opened, edited, and often even uploaded to a server, or possibly merged into the main branch of the project before a change can be viewed.