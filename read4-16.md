# summary class 16

## Event Driven Programming
we using event driven to avoid issues of complexity and collision.
everything in JS is an object and most actions in JS are event driven UI Events, Express Routes, (soon) Model, Lifecycle Hooks and (later) React … everything.
by event driven you can use this concepts (event Handler), which is a callback function that will be called when an event is triggered and a main Loop listens for event triggers and calls the associated event handler for that event.


## Emitting Events
is provided from node.js. we have EventEmitter2 and EventEmitter3 from npm both built to allow for syntax that is almost identical to what we’ll use for EventEmitter so learning one will make it easy to work with all of them.

EventEmitter is a class.
you can use removeListener or removeAllListeners to remove event listeners in EventEmitter. All objects that emit events are instances of the EventEmitter class. These objects expose an eventEmitter.on() function that allows one or more functions to be attached to named events emitted by the object. 


## Method of events
`eventEmitter.on()` used to register listeners, `eventEmitter.emit()` used to trigger the event. `emitter.off(eventName, listener)`, `emitter.prependListener(eventName, listener)`.