# Summary class 10

## Call Stack
A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions. Also, is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

Ex about call stack:
function greeting() {
   // [1] Some codes here
   sayHi();
   // [2] Some codes here
}
function sayHi() {
   return "Hi!";
}
greeting();

## Types of error messages
1. Reference errors *use a variable that is not yet declared*
2. Syntax errors
3. Range errors
4. Type errors

## debugging
the most important thing to can make a debugging know whats is the excution and stacks. we can use console to find the error. Also, we can use *breakpoint* to pause the code. you can use also the console to test line before you write it in code.

we can use for debugging call stack and console.log;
