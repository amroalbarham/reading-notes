***Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.***

***The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options listed in the documentation.***

- **The <'canvas'> element :**

**At first sight a <'canvas'> looks like the <'img'> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the <'canvas'> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.**

- **Drawing rectangles**
***There are three functions that draw rectangles on the canvas:***
   - *fillRect(x, y, width, height) Draws a filled rectangle.*
   - *strokeRect(x, y, width, height) Draws a rectangular outline.*
   - *clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.*
- **Drawing paths**
   - *beginPath() Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.*
   - *closePath() Adds a straight line to the path, going to the start of the current sub-path.*
   - *stroke() Draws the shape by stroking its outline.*
   - *fill() Draws a solid shape by filling the path's content area.*
   
