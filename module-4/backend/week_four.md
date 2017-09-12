## Week Four - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's your favorite project management tool?
 -- Pivotal Tracker: It's complex, which made it off-putting when it was first assigned/required for a project, but in time I learned to appreciate its nuances and features.
 
2. Why do we create staging environments?
 -- We need a place that mimics production in order to run new code and gauge its effects on the application. Staging is a great place to test new features without risking adverse affects to the live environment.
 
3. What are the characteristics of a good README (in your opinion)?
 -- It needs to have the following: installation instructions, code examples, how to contribute, and definitely gifs.
 
4. What's one main improvement you're going to make to your code regarding accessibility issues?
 -- The tabindex is definitely an easy one to implement and its benefits span several accesssibility areas.
 
5. What are some basic security concerns to be aware of when building applications?
 -- Scoping info to logged-in users instead of just a user-id. Require strong passwords and avoid having admins with user-id of 1.
6. Why is continuous integration helpful/important?
 -- The more tests are automated the more they will be run, period. CI prevents code that breaks the app from being pushed to production.
 
7. What are some continuous integration tools?
 -- Travis CI and Semaphoreci are two that I've used.

#### Review  

8. What are some characteristics of "good" git workflow?
 -- Mandatory PR reviews, commit small and often (with an eye on the feature's requirements), and make sure to check out feature branches that can be pushed to a development or test branch before going to master. Make good comments on the commit and use a template to describe the features of the PR so you and others can easily ascertain the purpose of that PR down the road.
 
 
9. What are the four fundamental concepts of object oriented programming?
 -- Encapsulation, Inheritance, Polymorphism, and Abstraction.
 
10. What's a module in Ruby and what's the difference between a class and a module?
 -- A module makes for easy accessibility of code you want to use in multiple other places. It might be code that pertains to a class, but not necessarily every instance of that class. So, some instance of a class might inherit code from a module, which another might not. One main difference between a Class and Module is that only a Class is initialized. 
