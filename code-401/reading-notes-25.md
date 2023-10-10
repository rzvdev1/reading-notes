# Context API

## Choosing the State Structure

Summarize the five principles for structuring state.

- the five principles for structuring state are:

1. Group related state. If you always update two or more state variables at the same time, consider merging them into a single state variable. 2. Avoid contradictions in state. When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this. 3. Avoid redundant state. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state. 4. Avoid duplication in state. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can. 5. Avoid deeply nested state. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.

## Passing State Deeply with Context

What problem do Contexts aim to solve?

- context solves the problem of having to pass props through intermediate elements
  What is one technique to try before useContext?
- one technique to try before useContext is to use props
  What hook complements useContext for complex applications?
- useReducer complements useContext for complex applications

-

### Resources I use

State structure[^1] and context[^2]

[^1]: [React](https://react.dev/learn/choosing-the-state-structure)
[^2]: [React](https://react.dev/learn/passing-data-deeply-with-context)
