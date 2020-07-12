# Combined Reducers

is using for combined many reducers, create object and each key in object is reduce. each reducer technically has it’s own actions and creators. combineReducers is a higher-order reducer.

the benefites of combineReducers are can use it at all levels of your reducer structure, not just to create the root reducer and combineReducers enforces several rules to help users avoid common errors.

There are two ways to define the initial shape and contents of store state. First, the createStore function can take preloadedState as its second argument.

the way of using combineReducers for Example:
[
import todos from './todos'
import counter from './counter'

export default combineReducers({
  todos,
  counter
})
]
