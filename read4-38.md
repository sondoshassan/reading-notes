# Asynchronous Actions

we using asynchronous when use Api, there are two crucial moments in time: the moment you start the call, and the moment when you receive an answer (or a timeout).

the way to use async action, use the Redux Thunk middleware. It comes in a separate package called redux-thunk. there is just one important thing you need to know: by using this specific middleware, an action creator can return a function instead of an action object. This way, the action creator becomes a thunk.

When an action creator returns a function, that function will get executed by the Redux Thunk middleware. This function doesn't need to be pure; it is thus allowed to have side effects, including executing asynchronous API calls. The function can also dispatch actions—like those synchronous actions we defined earlier.

## Redux Thunk
is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the body of the function once the asynchronous operations have completed.