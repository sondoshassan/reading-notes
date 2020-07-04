# summary class 31

## Hooks Api
are functions that let you “hook into” React state and lifecycle features from function components. React hook allows create and manage state. hooks named be used prefix use, you have not call hook inside loops, conditions, or nested functions.



## useState()
we pass to useState only argument to the useState() Hook is the initial state. Unlike with classes, the state doesn’t have to be an object. We can keep a number or a string if that’s all we need.

we use the square bracket when declare a variable of useState.

## useEffect()
adds the ability to perform side effects from a function component. It serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount in React classes, but unified into a single API. 

useEffect telling React to run your “effect” function after flushing changes to the DOM.