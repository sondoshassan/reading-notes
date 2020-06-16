# summary class 19

## Message Queues
The Queue server has the ability to see which clients are connected. 
message is a package of information, categorized by queue and event, queue which general bucket does this message belong like database event, event what event has happened like error or lost connection and payload data associated with the event.

### Real Time vs Queued Messaging
A true **Queue** will keep track of the delivery status of every event/message. In this type of systems, rather than a broadcasting of messages, clients will likely “poll” the server to retrieve any messages “in the queue” for them, on their own timeline/schedule.

### Namespace
 provides a scope  (the names of types, functions, variables, etc) inside it. Namespaces are using to organize your code into logical groups and to prevent name collisions that can occur especially when your codebase includes multiple libraries.