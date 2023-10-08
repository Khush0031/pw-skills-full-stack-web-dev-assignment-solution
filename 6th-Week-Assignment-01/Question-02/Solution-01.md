## Problem Statement

Explain the difference between Absolute and Relative positioning.

## Solution

Absolute and relative positioning are two commonly used concepts in web design and CSS (Cascading Style Sheets) that determine how elements are displayed on a webpage. 
They are used to control the layout and positioning of elements, such as text, images, and other HTML elements, within the web page's content. 

### 1. Absolute Positioning:

- Absolute positioning is a CSS property that allows you to precisely position an element relative to its nearest positioned ancestor or to the initial containing block (usually the browser window).
- When you use absolute positioning, the element is taken out of the normal flow of the document, which means it won't affect the positioning of other elements. It "floats" above or below the other content.
- To position an element absolutely, you specify its `top`, `right`, `bottom`, or `left` properties in relation to the nearest positioned ancestor or the initial containing block.
- Absolute positioning is often used for elements like tooltips, pop-up menus, or fixed navigation bars that should stay in a specific location regardless of how the page is scrolled or resized.

### 2. Relative Positioning:

- Relative positioning is another CSS property that allows you to move an element relative to its normal position in the document flow.
- When you use relative positioning, the element retains its space in the document flow, and the surrounding elements are not affected by it.
- To position an element relatively, you specify its `top`, `right`, `bottom`, or `left` properties with values such as pixels or percentages to adjust its position relative to where it would normally be placed.
- Relative positioning is often used for fine-tuning the layout of elements or creating small adjustments to an element's position within its containing block.

 The main difference between absolute and relative positioning lies in how they affect the flow of other elements on the page:

- Absolute positioning removes an element from the normal document flow and positions it relative to a specific ancestor or the initial containing block. This can potentially overlap with other content.
- Relative positioning moves an element within its normal position in the document flow, allowing you to make adjustments without affecting the surrounding elements.


