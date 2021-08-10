# Advanced State with Reducers

- **How can we ensure that an effect hook runs only once?**

    *If we pass an empty array [] , it just renders the component only once like componentDidMount.*

- **Can useState() update more than one state variable at the same time?**

    *we could do one setState call and there will only be one render. Unlike the setState in class components, the setState returned from useState doesn’t merge objects with existing state, it replaces the object entirely.*


- **Is useState() synchronous?**

    *Both useState and setState are asynchronous operations. The useState and setState methods do not return promises, despite the fact that they are asynchronous. As a result, we can't utilize async/await to obtain the updated state values or attach a then handler to it.*

***State Hook:*** **Allows you to utilize state and other React capabilities without having to write a class with a function component Component Lifecycle: The component's lifecycle functions are run in a predictable sequence. In general, the lifecycle methods of React components may be divided into four phases: initialization, mounting, updating, and unmounting.**


**How does useReducer work?**

  1. *useReducer is used to store and update states, just like the useState Hook. It accepts a reducer function its first parameter and the initial state as the second*

  2. *useReducer is one of the additional Hooks that shipped with React 16.8. An alternative to the useState Hook, it helps you manage complex state logic in React applications. When combined with other Hooks like useContext, useReducer can be a good alternative to Redux or MobX — indeed, it can sometimes be an outright better option.*

  3. *There are three main building blocks in Redux:*

      - *A store — an immutable object that holds the applications state data*
      - *A reducer — a function that returns some state data, triggered by an action type.*
      - *An action — an object that tells the reducer how to change the state. It must contain a type property, and it can contain an optional payload property const initialState = { count: 0 }*

  4. *const [state, dispatch] = useReducer(reducer, initialState) The reduce() method in JavaScript executes a reducer function on each element of the array an and then returns a single value.*

  5. *There are two different ways to initialize the useReducer state.*


  **When to use the useReducer Hook:**

  *When to use the useReducer Hook: Once your application grows in size, you’ll most likely deal with more complex state transitions. At this point, you will be better off using useReducer as it gives us more predictable state transitions than useState. This becomes more important when state changes become so complex that you want to have one place (i.e., the render function) to manage state.*


