# useState Hook

## Thinking in React

Summarize the five steps of thinking in react.

1. Break The UI Into A Component Hierarchy
2. Build A Static Version in React
3. Find4 The Minimal but complete Representation Of UI State
4. Find Where Your State Should Live
5. Add Inverse Data Flow

## State: A Component’s Memory

What is one reason a local variable isn’t sufficient for managing a React component?

- A local variable isn’t sufficient for managing a React component because it can’t be used to store data that changes over time.
  What is the argument to the useState hook, and what are the two parts of its return array?
- The argument to the useState hook is the initial state. The two parts of its return array are the current state and a function that updates the state.
  How can Component A access state from Component B?
- Component A can access state from Component B by passing the state of Component B to Component A as a prop.

### Reflection

1. What are your learning goals after reading and reviewing the class README?

- learn useState hook
- learn useEffect hook
- react lifecycle
- pros and cons of using functional components vs class components

### Resources I use

Thinking in React[^1] and State[^2]

[^1]: [React](https://react.dev/learn/thinking-in-react)
[^2]: [React](https://react.dev/learn/state-a-components-memory)
