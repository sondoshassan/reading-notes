# summary class 36

## Redux
is a library. is a predictable state container for JavaScript apps. it is advisable to store your application state in a single object managed by the Redux store. The only way to change the state is to emit an action, an object describing what happened. is an application data-flow architecture, rather than a traditional library or a framework like Underscore.js and AngularJS. by using Redux You can access state values directly from the store

the steps to use Redux:
first install redux then import createStore, use reducer as a store-> createStore(reducer), state and action pass on reducer. Store.getState() will return the current state of your application. 


we use to test Redux enzyme and jest. the benefit of using jest you can easily setup framework, ability to run tests in parallel, it has snapshot testing and code coverage is available right out of the box.

