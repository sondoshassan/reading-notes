# summary class 32

## Custom Hooks
that mean you can bulid your own hooks, and use it with prefix use. any thing is function can become a hook. useEffect maybe render after each update or render at the first.

It likes something we may want to do on several pages or inside numerous different functional components in our app. When information changes we want to update the document title with some type of string. Additionally, we don't want to repeat this logic inside every functional component. 

you can call the custom hook by useEffect. the benefit of use custom hook to DRY.

## useReducer 
is preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.