## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?
 -- Node is a server-side framework that runs on Chrome's V8 Javascript engine. It comes with a package manager called NPM and has a non-blocking I/O protocol (probs not the right word).
 
2. What is Express? Why is Express similar to in the Ruby world?
 --Express is a Node web-server that simplifies much of the necessary steps needed to effectively build a web application on Node.
 
3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
 --You need to require `express` and then use it to make a new route:
 ```
 express = require('express')
 app = express()
 
 app.get('/some/route' function(req, res) {}
 ```

4. What do we use Knex for?
 --Knex is for making SQL queries.
 
5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?
 --Organize using a directory structure such as Client, App, Server. The client would hold your assets, the app would have most of the model files, while the server would have your routes and related config.
 
6. How do you execute raw SQL in node?
 --you can use the `raw` function on your db. something like db.raw('SQL').
 
7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
 --With separation it might be easier to form and maintain complex interactions with the front-end. The main disadvantage is getting the separate apps to talk to each which can make things like security/authorization more difficult.

#### Review  

8. Describe DNS.
 --Domain Name Service, which provides a pointer to the server on which an app is hosted. It's basically an address.
 
9. What does writing clean code mean to you?
 --Clean code is code that uses built-in functions, separates responsibility, and maintains conventions. It also means having consistent organizational patterns and using packages as if you know what they do.
 
10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?
 --A hotel app would need rooms, guests, bookings, locations, and amenities at least. A `guest` would create the `booking`.
