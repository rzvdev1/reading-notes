# Additional Topics

## Redux Toolkit (RTK)

What concerns are addressed by Redux Toolkit?

- redux toolkit address the following concerns of boilerplate code and mutate the state directly.

What does configureStore() do?

- the configureStore() does the following, combines all the reducers, use thunk middleware, use the `createAction` and `createReducer` functions

How would I use createSlice()?

- the createSlice() is used to create a reducer function and action creators for a given slice of state and it will automatically generate action types that correspond to the action creators and reducers.

## MobX

What is Mobx?

- MobX is a simple, scalable and battle tested state management solution and a standalone library.

How does MobX make it “impossible” to produce an inconsistent state?

- the MobX makes it impossible to produce an inconsistent state by making sure that all the state is derived from the minimal possible state.

How would we build a reactive user interface?

- we can build a reactive user interface by using the `@observer` decorator on React components.

# Tutorial

What take-away(s) did this tutorial provide?
https://redux-toolkit.js.org/tutorials/overview

- the take away from this tutorial is that the redux toolkit is a package that is used to simplify the redux development process and it is used to reduce the amount of boilerplate code that is needed to update the store.
- the redux toolkit is used to simplify the redux development process by using the `configureStore()` function to combine all the reducers, use thunk middleware, use the `createAction` and `createReducer` functions.
- rtk is used to reduce the amount of boilerplate code that is needed to update the store by using the `createSlice()` function to create a reducer function and action creators for a given slice of state and it will automatically generate action types that correspond to the action creators and reducers.
- use the `createAsyncThunk` function to handle async logic and dispatch actions based on the results of the async logic.

### Reflection

What are your learning goals after reading and reviewing the class README?

- plan to learn redux toolkit and mobx
- use Alternate Redux Store Managers ducks
- migration of simple Redux to either Ducks or Toolkit

### Resources I use

Redux toolkit[^1], MobX getting started[^2], and the redux tutorials overview[^3]

[^1]: [Redux](https://redux-toolkit.js.org/introduction/getting-started)
[^2]: [MobX](https://mobx.js.org/getting-started.html)
[^3]: [Redux](https://redux-toolkit.js.org/tutorials/overview/)
