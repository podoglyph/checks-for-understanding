## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's one difference between ES5 and ES6?
 --In ES6 it's much easier to define classes using keywords `class`.
 
2. What's the difference between asynchronous and synchronous JavaScript?
 --In synchronous JS each request/event/function must be executed to completion before the program can execute the next function. In async, the computer will begin to execute a function from the stack, and send it to finish, and return it to the queue, while other functions continue to be interpreted and exectued.
 
3. What are the four pillars of Object Oriented programming?
 --Encapsulation, Polymorhphism, Inheritance, Abstraction.
 
4. What are some tools available in JavaScript to help you write object oriented code?
 --The `class` keyword and `contructor` functions.
 
5. What are some key concepts to be aware of when refactoring your JavaScript?
 --Closures and currying can be useful to write clean, readable, and efficient code. Separate the event listeners and handlers in order to have single-responsibility as much as possible.
 
6. What's a callback function and what are some reasons when we use/need callback functions?
 --Callbacks are great for things like event listeners. They are functions called by other functions. They can be used to handle errors.
 
7. What's the scope of variables in Javascript?
 --Global if defined without a keyword, local to functions using `let` or `var`.
 
8. What's the difference between `==` and `===` in JavaScript?
 --The latter checks for `type`, as well.
 
9. Why do front end frameworks exist?
 --To make it easier to communicate between the client and server, organize client-side files.

#### Review  

10. Why do people say "HTTP is stateless"?
 --Because on refresh you lose all `state` unless you code in a session or some equivalent.
 
11. Describe a RESTful API.
 --An API organized using common naming conventions such as Index and Show, which makes it easy to understand the architecture of the API endpoints.
 
12. What are some main characteristics of a team following an agile workflow?
 --They use an iterative, test-driven approach, communicate effectively, shoot for small, incremented feature additions.
 
13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?
 --It's easy for the user and you don't have to store sensitive user data on your server, but you don't get access to everything you need or want by not having your own authorization.
