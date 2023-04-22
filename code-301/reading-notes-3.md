# Hello

This topic matters beacuase understanding the understanding passing props in react is the core concept. As a developer we need to know this functionality and learn to work with it.

The map returns a new array. In JSX using curly braces {} to loop through array. Each list item needs a unique key. The purpose of a key is items have changed, are added, or are removed.

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments. The four things the spread operator can do is:

- Copying an array
- Concatenating or combining arrays
- Using an array as arguments
- Combining objects

An example of using the spread operator to combine two arrays.

const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]

Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) // Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

Give an example of using the spread operator to combine two objects into one.

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

The first thing to pass functions between components are parent component to a child component. The increment functions increase an item by one. To pass a method from a parent component into a child component is through props. The child component invoke a method that was passed to it from a parent component you will use this.increment.

## Things I want to know more about

1. Does the server read the JSX file?

2. Are there any drawback using the spread operator?

### Resources I use

Lists and Keys,[^1] the Spread Operator,[^note] and How to Pass Functions between Components.[^skill]

[^1]: [React](https://legacy.reactjs.org/docs/lists-and-keys.html)
[^note]: [JavaScript](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
[^skill]: [Youtube](https://www.youtube.com/watch?v=c05OL7XbwXU)
