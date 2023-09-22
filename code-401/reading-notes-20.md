# Component Based UI

## React Quick Start

1. What are the building blocks of a React app?

   The building blocks of a React app are components.

2. What is the difference between an HTML element and a React component?
   An HTML element is a tag that is used to define the structure of a web page. A React component is a function or class that produces HTML to display content to the screen.
3. What is JSX and why do we use it?
   JSX is a syntax extension to JavaScript. It allows us to write HTML in React. We use it because it is easier to write than JavaScript.
4. Describe the process of embedding JavaScript expressions in JSX.
   We embed JavaScript expressions in JSX by wrapping them in curly braces.
5. Does React or JSX have any special features for iteration or conditional logic?
   React has special features for iteration and conditional logic. We can use the map() method to iterate over an array of items and render each item to the screen. We can use the if statement to conditionally render an element.
6. How does React know to respond to a user’s inputs?
   React responds to a user’s inputs by using event handlers.
7. What word indicates that a React component manages data with a Hook?
   The word useState indicates that a React component manages data with a Hook.
8. How can two react components share data?
   Two react components can share data by using props.

## Render and Commit

1. What are the three steps of refreshing a React UI?
   Triggering a render, Rendering the component, and Committing to the DOM
2. How do you trigger updates to a component after the initial render?
   You trigger updates to a component after the initial render by calling the setState() method.
3. Does React recreate DOM nodes on every rerender?
   No, React does not recreate DOM nodes on every rerender.
4. After React has updated the DOM, what still needs to happen before the user sees the change?
   After rendering is done and React updated the DOM, the browser will repaint the screen. Although this process is known as “browser rendering”, we’ll refer to it as “painting” to avoid confusion throughout the docs.

### Additional Questions

- In the Airbnb React/JSX Style Guide I see the use of PascalCase for React components and camelCase for their instances.
- Looking ahead at this module’s course schedule, I look forward to learning more about data structures and algorithms, functional components, and React Hooks.
- My goals after reading and reviewing the class README are to learn more about SASS, functional components, and JSX.

### Resources I use

Learn React [^1], Render & Commit[^2], and Airbnb React/JSX Style[^3]

[^1]: [React](https://react.dev/learn)
[^2]: [React](https://react.dev/learn/render-and-commit)
[^3]: [Airbnb](https://airbnb.io/javascript/react/#naming)
