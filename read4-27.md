# summary class 27

## React Testing
by using:

### shallow

for test components in isolation from the child components they render.  is useful to constrain yourself to testing a component as a unit, and to ensure that your tests aren't indirectly asserting on behavior of child components.

### React Testing Library
is a library for testing React components in a way that resembles the way the components are used by end users. It works more directly with DOM nodes, and therefore it's recommended to use with jest-dom for improved assertions.

### Snapshot testing

by using jest. useful when you want to make sure your UI does not change unexpectedly. Jest uses pretty-format to make snapshots human-readable during code review.


### Mountiong

Full DOM rendering is ideal for use cases where you have components that may interact with DOM APIs or need to test components that are wrapped in higher order components. need to run in  a browser environment.

## Deployment
React uses a node service to create a live website that refreshes as you write code. `npm run build` excuted  from the root folder in React application. 