# summary class 02

## Answer questions
1- Name 3 advantages to Test Driven Development?

there are many advatages of TTD but I will mention three: recive fast feedback, reduce time spent on rework and support clean interface.

2- In what case would you need to use beforeEach() or afterEach() in a test suite?
we use this two methods to perform operation before the test run and after the test finish.
this is useful if you want to cleanup state by each test created.

3- What is one downside of Test Driven Development
it take a long time to investment.

4- What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
the classes are description fo object, In the classes we use contructor, and use `super()`.
the Constructor used new as a keyword and is working object instance.

5- Name a use case for a static method
without instantiating.
we used to assgin a method in class (like prototype in constructor)

6-Write an example of a Higher Order function and describe the use case it solves
the `map` in array is ahigher order function because is used another function.
it takes a nother function as argument 
map: its return a new array by using the another array and function and without change the original array.

## videos 
it talk about how to decrease the costs of maintenance, the test will be excutable in all browser, TDD to improve the code and focus on the code without looking for previous code and it is relevant to Javascript.

this is we know from previous course is refer to window. window is a defult context. We can change the context by call, apply and bind. apply take two args the new context and array. bind takes one arg.

prototype chain: as simple is the prototype inside another prototype.
Class: is a speacial function, we have two types of function which are decleration and expression. we use extend to make a copy from another class. we use `Object.setPrototypeOf()` to make a function as a prototype of class.
jest: is using to test the code. we can install it by using this command *npm install --save-dev jest* Or *yarn add --dev jest*
