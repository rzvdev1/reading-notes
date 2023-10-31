# Redux - Combined Reducers

## Multiple Reducers Example

Why create multiple reducers?

- You can create multiple reducers to handle different parts of your application state in isolation.

  How would you combine multiple reducers?

- You can combine multiple reducers using the `combineReducers` function from the redux library.

  How will you manage state as an immutable object? why?

  - You can manage state as an immutable object by using the `useReducer` hook from react. This is useful because it allows you to manage state in a more predictable way.

## Redux Docs: Using Combined Reducers

combineReducers is a utility function to simplify the most common use case when writing **\_ \_\_\_** .

- Redux reducers.

Explain how combineReducers assembles the new state tree.

- the combineReducers assembles the new state tree by combining multiple reducers into one reducer function.

How would you define initial state in an app using combineReducers?

- you define the initial state in an app using combineReducers by passing an object whose values are different reducing functions into a single reducing function you can pass to createStore.

## Redux Docs: Combined Reducer Syntax

Why will you want to split your reducing functions as your app becomes more complex?

- You will want to split your reducing functions as your app becomes more complex because it allows you to manage state in a more predictable way.

The **\_** helper function turns an object whose values are different reducing functions into a single reducing function you can pass to \_\_\_\_.

- The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

What is a popular convention when naming reducers?

- A popular convention when naming reducers is to name them after the state slices they manage.

### Reflection

What are your learning goals after reading and reviewing the class README?

- better understanding of redux and how to use it
- using multiple reducers in redux
- combining reducers in redux
- sharing actions between reducers

### Resources I use

Multiple Reducers with Redux Reducers[^1], Using combineReducers[^2], and combineReducers(reducers)[^3]

[^1]: [YouTube](https://www.youtube.com/watch?v=gBER4Or86hE)
[^2]: [Redux Docs](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)
[^3]: [Redux Docs](https://redux.js.org/api/combinereducers/)
