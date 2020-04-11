# summary class 11

There are two ways to identify your application: 
1. using an OAuth 2.0 token (which also authorizes the request).
2. using the application's API key.

There are three types of IDs:
1. Volume IDs
2. Bookshelf IDs: Numeric values given to a bookshelf in a user's library.
3. User IDs.

## EJS 
is a simple templating language that lets you generate HTML markup with plain JavaScript.

first you need to install the EJS: npm install ejs.
then pass EJS a template string and some data.
download a browser build from the latest release, and use it in a script tag.

you can use if and for in ejs.

- set to the engine to ejs
app.set('view engine','ejs');
- // index page 
app.get('/', function(req, res) {
    res.render('pages/index');
});
- // about page 
app.get('/about', function(req, res) {
    res.render('pages/about');
});

- // index page 
app.get('/', function(req, res) {
    var drinks = [
        { name: 'Bloody Mary', drunkness: 3 },
        { name: 'Martini', drunkness: 5 },
        { name: 'Scotch', drunkness: 10 }
    ];
    var tagline = "Any code of your own that you haven't looked at for six or more months might as well have been written by someone else.";

    res.render('pages/index', {
        drinks: drinks,
        tagline: tagline
    });
});
- app.listen(8080);
console.log('8080 is the magic port');
