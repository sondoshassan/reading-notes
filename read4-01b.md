# Summary Read 01 401 class

In this reading, I will answer questions and then summarize the article and video.

## The Questions and Answers
1- Why would you want to run JavaScript code outside of a browser?
at the first, we need to know whats the mean of run js outside the browser. run js outside the browser that's mean you are using node.js to execute the code, which is referred to the back-end. So we run js outside in the back-end programming which will interact with a database and use it to build API.

2- What is the difference between a module and a package?
as simple as the module is a single file but the package contains multiple modules.

3- What does the node package manager do?
It helps us to use node.js and to manage the dependencies. Also, provide package-lock.json which display all dependencies. we can use it to manage multiple versions of code and code dependencies and globally-installed project’s tools.

4- Provide code snippets showing 3 different ways to export a function from a node module
- first way export anonymous function
Ex:
module.exports = function (msg) { 
    console.log(msg);
};

- second way export function as class
Ex:
module.exports = function (firstName, lastName) {
    this.firstName = firstName;
    this.lastName = lastName;
    this.fullName = function () { 
        return this.firstName + ' ' + this.lastName;
    }
}

- third way 
let myFunc1 = function() { ... };
let myFunc2 = function() { ... };
exports.myFunc1 = myFunc1;
exports.myFunc2 = myFunc2;

## npm
npm is a node package manager, npm make share the code easy and to reuse this code and it is easy to check the update they made. the npm works when the developer share thier code and then the npm client install it they publish the code up to registry and then other developers can search this package into registry. then as they say before the most benefit of npm to share the code between developer and reuse it and make it easy to manage the different version of code.

registry is a large database of javascript.
