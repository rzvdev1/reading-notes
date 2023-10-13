# Context API - Behaviors

1. How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)

- the useReducer and useContext works together by using the reducer function to update the state and the useContext to pass the state to the components that need it. By using the reducer function we can update the state in a more efficient way and by using the useContext we can pass the state to the components that need it without having to pass it down as props. There is no need to use a react third party library like redux to manage the state of the application.

-

### Resources I use

scaling up with reducer and context[^1]

[^1]: [React](https://react.dev/learn/scaling-up-with-reducer-and-context)
