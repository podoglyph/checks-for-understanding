## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
 --Learning about `this` was super important.
 
2. What are some tools to help debug JavaScript code?
 --The `debugger` and just go ahead and `console.log()` everything!
 
3. What are some tools you need in order to unit test your JavaScript?
 --Mocha and Chai, and now Selenium.
 
4. What is the syntax for invoking a function?
 --Don't forget the parentheses after the name. Pass in any parameters you'll need.
 
5. What is CORS?
 --Cross Origin Resource Sharing. I think it's referencing the use of resources from other domains. Grabbing stuff to bring render on the DOM.
 
6. How do we enable CORS?
 --I don't know off the top of my head.
 
7. What's `this` in JavaScript?
 --It's a contextual object that contains stuff based on where it was invoked.
 
8. What is Webpack and why is it useful?
 --Webpack grabs all your assets and js and puts them together into a neat little package to send over the DOM.
 
9. When/why do you want to use event delegation?
 --Event delegation is used for having listeners on things added dynamically to the DOM. If a user could add 100 new things, and you want to listen for action on those things, you wouldn't want a new listener for each thing. Instead, put the listener on a parent element that's present when the DOM is loaded.
 
10. What is a callback function?
 --More or less a function that executes when after another one.
 
11. What's `npm` and what do we use it for?
 --Node Package Manager. npm packages are like Gems. They give us more functionality and are easily installed.
 
#### Review  
12. What's the MVC design pattern? Describe each part of MVC.
 --Model, View, Controlller
  --Model is the `thing` or `object` that contains mehtods you'd use to manipulate data before sending it off to the View.
  --View is the DOM, what the user sees and interacts with.
  --Controller delegates what's brought back from the DB for the model to do stuff on before sending it back to the client.
  
13. What are a few ways to optimize a Rails application?
 --Precompile assets. Make specific queries to the DB so you don't pull out more than need to send to the client. Enable caching.
 
14. What's a background worker? When would we want to use a background worker?
 --It executes scripts while the app continues to run. Sending an email to a user is a good example.
