# Advanced State with Reducers

# Extracting State Logic into a Reducer

1. What is the motivation for adding a reducer?

- the motivation for adding a reducer is to extract the state logic from the component to make it easier to test and reuse.

2. What are actions in the context of a reducer? How are they different than setting state directly?

- the actions in the context of a reducer are the actions that are dispatched to the reducer. They are different than setting state directly because they are not setting the state directly, they are dispatching an action to the reducer to set the state.

3. What common list operation is useReduce named for, and why?

- the common list operation that useReduce is named for is the reduce method. It is named for this because it is used to reduce a collection of values down to a single value.

4. When should you switch from useState to useReducer?

- you would switch from useState to useReducer when you have a complex state logic that involves multiple sub-values or when the next state depends on the previous one.

### Reflection

1. What are your learning goals after reading and reviewing the class README?

- use the reducer hook
- dispatch actions to a reducer hook
- payload and action types

### Resources I use

useReducer[^1]

[^1]: [React](https://react.dev/learn/extracting-state-logic-into-a-reducer)
