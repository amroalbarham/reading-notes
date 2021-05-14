## Object
------------
### Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.



**IN AN OBJECT: variables become known as propertied and The value of a property can be a string, number, Boolean, array, or even another object.**

**IN AN OBJECT: functions become known as methods  and The value of a method is always a function.**

### The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.



### Accessing and updating the DOM tree involves two steps:
1. **Locate the node that represents the element you want to work with.**
    1. ***SELECT AN INDIVIDUAL ELEMENT NODE:***
        - *Uses the value of an element's id attribute -Uses a CSS selector, and returns the first matching element.*
        - *You can also select individual elements by traversing from one element to another within the DOM tree*
    2. ***SELECT MULTIPLE ELEMENTS (NODELISTS):***
        - *Selects all elements that have a specific value for their cl ass attribute.* 
        - *Selects all elements that have the specified tag name.* 
        - *Uses a CSS selector to select all matching elements.*
    3. ***TRAVERSING BETWEEN ELEMENT NODES:***
        - *Selects the parent of the current element node (which will return just one element).*
        - *Selects the previous or next sibling from the DOM tree.*
        - *Select the first or last child of the current element.*

2. **Use its text content, child elements, and attributes.**


----------------------


+ **The browser represents the page using a DOM tree**
+ **DOM trees have four types of nodes: document nodes,element nodes, attribute nodes, and text nodes.**
+ **You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax** 
+ **Whenever a DOM query can return more than one node, it will always return a Nadel i st.**
+ **From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques.**
+ **An element node can contain multiple text nodes and child elements that are siblings of each other.**  
+ **Browsers offer tools for viewing the DOM tree.**
