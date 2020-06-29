# summary class 28

## Forms and Inputs
in the input, it has onChange event that we can handle and use to update our form-container’s state each time the user interacts with an input. 

## Props
are passed into a component with a syntax that looks like HTML attributes. These are the equivalent of function params. props stands of properties. props is the name of the object passed into a component constructor and any prop added to a component in the JSX will be accessible as a property on props.

## setState()
is the only legitimate way to update state after the initial state setup. Object.assign() is used to copy data from a source object to a target object. when working with setState() for update to a component state should be done using setState(), you can pass an object or a function to setState(), pass a function when you can to update state multiple times and don't depend on this.state immediately after calling setState() and make use of the updater function instead.