# layout
Block-level elements start on a new line.

Inline elements flow in between surrounding text.

Controlling the Position of Elements

# Grid

define grid container element (parent) -> display: grid
set its column and row sizes -> grid-template-columns and grid-template-rows
place grid items (children) into the grid -> grid-column and grid-row
children are only the direct descendants of the parent element
Note: column, float, clear, and vertical-align have no effect on a grid container

# Terminology
grid container
grid item
grid line = The dividing lines that make up the structure of the grid.
grid track = column or row
grid cell = a single "unit" of the grid.
grid area = The total space surrounded by four grid lines. Can contain any number of cells.

# Normal Flow
position:static
In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow.

position:relative
Relative positioning moves an element in relation to where it would have been in normal flow.

position:absolute
When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page.

# Screen Sizes
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.


