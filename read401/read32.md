## Context API - Behaviors


- **When you have multiple contexts, what component type should you use (class/function) and why?**

    *The difference is pretty obvious. Class components are ES6 classes and Functional Components are functions. The only constraint for a functional component is to accept props as an argument and return valid JSX.*

- **What are some good use cases for using the Context API for global state?**

    -  **Twilio :** *Twilio really defines what it means to be API-driven.* 
    -  **Stripe :** *Stripe is one of the most successful and best known API-driven businesses.*
    -  **Ebay :** *Unlike the previous companies, eBay didn’t start out with the intent of being API-driven.*
    -  **Salesforce :** *XML APIs have been a part of Salesforce since day one, back in 2000 when it launched.*
    -  **Rovi :** *Rovi is definitely the oldest company on the list, founded as Macrovision in 1983.*


- **How can you best test context?**

    *The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing).*

- **context** *is designed to share data that can be considered "global" for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a "theme" prop in order to style the Button component: class App extends React.*


- **useContext()** *hook is used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level. Context defined will be available to all the child components without involving "props".*

- **static context**: *If you are using the experimental public class fields syntax, you can use a static class field to initialize your contextType.*

### Context api

  **Context provides a way to pass data through the component tree without having to pass props down manually at every level and In a typical React application, data is passed top-down (parent to child) via props, but such usage can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.**


  **Before You Use Context Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult and If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.**

  ## Hooks and context example

  **After performing an audit on how we communicate with our users, we landed with a simple system of three classes of communication, and snackbars fit perfectly on the 'low priority' end of that spectrum. They are small notifications that show up on the screen when a user performs an action. They are not intrusive at all and appear for just a brief moment.**

  