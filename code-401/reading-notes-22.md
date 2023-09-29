# Component Lifecycle / useEffect Hook

# useState Hook

## useEffect hook

1. What is the main intended use case for the useEffect hook?
   The main intended use case for the useEffect hook is to allow to run function components. Another use case is to save local storage.
2. How does the effect’s logic interact with the component?
   The effect’s logic interact with the component by using the useEffect hook and passing it a function. The function will run after the render is committed to the screen.`useEffect(() => { console.log('render'); });`
3. What is the importance of the return value from the effect’s logic function?
   The importance of the return value from the effect’s logic function is to clean up the effect and not have any memory leaks.

### Reflection

1. What are your learning goals after reading and reviewing the class README?

- learn useEffect hook
- Component Lifecycle
- Cleaning up a component on Un-Mount
- Watching state and other conditions

### Resources I use

useEffect[^1]

[^1]: [React](https://react.dev/reference/react/useEffect#reference)
