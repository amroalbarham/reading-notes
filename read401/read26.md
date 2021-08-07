# Component Based UI



- **Name 5 Javascript UI Frameworks (other than React)**

    *Angular, Vue, Ember, Svelte 3, Ext JS by Sencha*

    ![UI](./img/read26A.png)


- **What’s the difference between a framework and a library?**

     *The technical difference lies in a term called inversion of control. When you use a library you are in charge of the flow of the application ( you are choosing when and where to call the library), but when you use a framework it is in charge of the flow (provides some places for you to plug in your code but it calls the code you plugged in as needed.*  


**Rendering :** *Rendering refers to showing the output in the browser.*

**Templates :** *Templating refers to the client side data binding method implemented with the JavaScript language.*

**State :** *Describes the status of the entire program or an individual object.*

**JSX** 

![JSX](./img/read26B.png)

- *JSX produces React “elements”.*

- *React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.*

- *React separates concerns with loosely coupled units called “components” that contain both.*

- *React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code.* 

- *It also allows React to show more useful error and warning messages.* 

- *You can put any valid JavaScript expression inside the curly braces in JSX.*

- *After compilation, JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects.*

- *If a tag is empty, you may close it immediately with />.* 

- *JSX tags may contain children.*

- *React.createElement() performs a few checks to help you write bug-free code but essentially it creates an object.*

- *An element describes what you want to see on the screen.*

- *React elements are plain objects, and are cheap to create.*

- *Applications built with just React usually have a single root DOM node.*

- *To render a React element into a root DOM node, pass both to ReactDOM.render().*

- *React elements are immutable : Once you create an element, you can’t change its children or attributes.*