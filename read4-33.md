# summary class 33

## Context
is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. is primarily used when some data needs to be accessible by many components at different nesting levels. component composition is often a simpler solution than context. 

In React, data is passed top-down (parent to child) via props, but this can be cumbersome for certain types of props that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a props through every level of the tree.

you can update context from a nested component from a component that is nested somewhere deeply in the component tree.

context.provider allows consuming components to subscribe to context changes.