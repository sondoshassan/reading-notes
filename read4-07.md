# summary class 07

## Express
is a package for web framework for node.

it takes the request from client side and then send the response. the request is an object have aparameters or query. and response also an object send the data back to browser has two methods `send` and `status`. by res can send header, cookies and status code.

## Express Middleware
is a web framework, take a request(object) and response(object) and text middleware. By middleware function can execute any code, make changes to the request and the response objects, end the request-response cycle and call the next middleware function in the stack.

## Routing
it is the end point of url, you can define it by using *app.get()*, *app.post()*, *app.use()* and *app.all()*. it's important to add next as an argument to the callback function and then call `next()` within the body of the function to hand off control to the next callback.

### EX of using next:
app.get('/example/b', function (req, res, next) {
  console.log('the response will be sent by the next function ...')
  next()
}, function (req, res) {
  res.send('Hello from B!')
})

## Server Testing
HTTP assertions made easy via superagent.

1- Units: Server Internal Functions
- Mock any integrations (like data fetching)
2- Integration: How it connects to other services
- Really connect to other services (hard dependencies)
3- Acceptance
- The server might be a dependency of some other test

