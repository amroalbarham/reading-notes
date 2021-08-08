## Hook


1. **How does React differ from vanilla JS/HTML/CSS?**

    - *Vanilla JS requires a lot of typing : JS requires a lot of codes so would be little messy and that make it less efficient than React.*

    - *React JS is for code organization :ReactJs is great for organizing the code. as you can see all the above code is on one page, script.js.*

    - *“React :A JavaScript library for building user interfaces. Lots of people use React as the V in MVC. Since React makes no assumptions about the rest of your technology stack, it’s easy to try it out on a small feature in an existing project”.*

    - *“Vanilla.JS: A fast, lightweight and cross-platform framework. It is a fast and cross-platform framework for building incredible, powerful JavaScript applications. it is the most lightweight framework available anywhere”.*


2. **What is the primary difference between a function component and a class component?**

    - *Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks*
    - *You end up with less code*
    - *They help you to use best practices. It will get easier to separate container and presentational components because you need to think more about your component’s state if you don’t have access to setState() in your component*
    - *The React team mentioned that there may be a performance boost for functional component in future React version*



**Functional Components:** *Functional components are basic JavaScript functions. These are typically arrow functions but can also be created with the regular function keyword. Sometimes referred to as “dumb” or “stateless” components as they simply accept data and display them in some form; that is they are mainly responsible for rendering UI.*

**Children / Child Components:** *There is one prop that gets special treatment unlike all the others. Children allow you to pass components as data to other components, just like any other prop you use.*

**Hooks :**  *“Hooks are an experimental proposal to React. You don’t need to learn about them right now. Also, note that this post contains my personal opinions and doesn’t necessarily reflect the positions of the React team”.*

**Use Hooks :** *“when we write a function component, and then we want to add some state to it, previously you do this by converting it to a class. But, now you can do it by using a Hook inside the existing function component”.*

**Using the State Hook :** *In a function component, we have no this, so we can’t assign or read this.state. Instead, we call the useState.*


***Hooks at a Glance :***

1. *“Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don’t work inside classes — they let you use React without classes. (We don’t recommend rewriting your existing components overnight but you can start using Hooks in the new ones if you’d like”.*

2. *“React provides a few built-in Hooks like useState. You can also create your own Hooks to reuse stateful behavior between different components. We’ll look at the built-in Hooks first”.*

3. *“The Effect Hook, useEffect, adds the ability to perform side effects from a function component. It serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount in React classes, but unified into a single API.”.*

4. *“When we call useEffect, we’re telling React to run your “effect” function after flushing changes to the DOM. Effects are declared inside the component so they have access to its props and state. By default, React runs the effects after every render — including the first render”.*

