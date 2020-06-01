# summary class 08

## Routing
is URL endpoint respond from client. you can define this route by using methods like `app.get()`, `app.post()`, `app.use()` and `app.all()`. these method using callbackfunction and maybe it has many callback function with provide next. and we need express dependency to define the route.

app.all() using to load middleware function at all path methods.

- to get instance of router: var router = express.Router();
you can create multiple express.Router() and then apply them to your application. you could have a Router for your basic routes, authenticated routes, and even API routes.