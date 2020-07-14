## Redux Toolkit
is intended to be the standard way to write Redux logic. 
this redux toolkit, it contains `configureStore()` wraps createStore to provide simplified configuration options and good defaults, `createAction()` generates an action creator function for the given action type string and `createAsyncThunk` accepts an action type string and a function that returns a promise, and generates a thunk.

## MobX
makes state management simple by addressing the root issue: it makes it impossible to produce an inconsistent state. The strategy to achieve that make sure that everything that can be derived from the application state, will be derived. Automatically.

## 