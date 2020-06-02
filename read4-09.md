# summary class 09

## Router
 you can run middleware only when certain parameters are present and expected. this function use name which params and callback function, By this way:
 [`router.param('city', function (req, res, next, id){
    console.log('Only runs on routes that have a city param')
    next()
});`]

## MiddleWare 
why we use middleware?
because it is useful for atomizing model logic. for example in complex validation, removing dependent documents, asynchronous defaults and asynchronous tasks that a certain action triggers.

### Subdocuments
are documents embedded in other documents. In mongoose thats mean the schema embedded in other schema. it has two distinct notions: *arrays of subdocuments* and *single nested subdocuments*. subdocumente have `save` and `validate` middleware. MongooseArray methods such as push, unshift and addToSet.

you can use match with populate() to add filter. You can populate in either pre or post hooks.

