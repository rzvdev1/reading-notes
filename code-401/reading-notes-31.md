# Redux - Asynchronous Actions

## async actions

Why use Redux middleware?

- redux middleware is a way to enhance redux's behavior with extra functionality

Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

- The flow a normal flow, except that the action creator returns a function instead of an action. The function is called by the middleware, and the function can dispatch actions, including the original action.

How are we accommodating async in our Redux app?

- We are using redux-thunk middleware to allow us to return a function instead of an action.

## thunk middleware

Why would you need redux-thunk middleware?

- We need redux-thunk middleware to allow us to return a function instead of an action.

Redux Thunk middleware allows you to write action creators that return a \_\_\_\_ instead of an action.

- function

Describe how any return value from the inner thunk function will be made available.

- The return value from the inner thunk function will be made available as the return value of the dispatch method.

### Resources I use

Redux async[^1] and thunk[^2]

[^1]: [Redux](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)
[^2]: [Thunk](https://github.com/reduxjs/redux-thunk)
