# Hello

This topic matters because these are the key points of react in order to make a web application work many react base webpages work the similar way. Knowing how to code react application with the fundamentals will only help you as a developer.

A single responsibility principle is a component should ideally only do one thing and apply to components by decomposed into smaller subcomponents. A static version of application is [components](https://react.dev/learn/your-first-component) that reuse other components and pass data using [props](https://react.dev/learn/passing-props-to-a-component). The only thing you need to add after static application is state. The three question you can ask if something is state is :

- Does it **remain unchanged** over time? If so, it isn’t state.
- Is it **passed in from a parent** via props? If so, it isn’t state.
- **Can you compute it** based on existing state or props in your component? If so, it *definitely* isn’t state!

You can identify where states live by

1. Identify *every* component that renders something based on that state.
2. Find their closest common parent component—a component above them all in the hierarchy.
3. Decide where the state should live:
   1. Often, you can put the state directly into their common parent.
   2. You can also put the state into some component above their common parent.
   3. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.

A higher-order function is Functions that operate on other functions, either by taking them as arguments or by returning them. The greaterThan function on line 2 it looks like it is returning an argument that the argument is greater than the parameter being passed. The map operates as an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been *mapped* to a new form by the function.

1. Is the App file only where that state can be located at?
2. I want to know more about the reduce method

### Resources I use

Thinking in React[^1] and Higher-Order Functions[^note]

[^1]: [React](https://react.dev/learn/thinking-in-react)
[^note]: [JavaScript](https://legacy.reactjs.org/docs/forms.html)
