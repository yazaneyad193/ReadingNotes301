# HEROKU

> is a cloud platform as a service (PaaS) supporting several programming languages.

>  One of the first cloud platforms, Heroku has been in development since June 2007, when it supported only the Ruby programming language, but now supports Java, Node.js, Scala, Clojure, Python, PHP, and Go.[1][2] For this reason, Heroku is said to be a polyglot platform as it has features for a developer to build, run and scale applications in a similar manner across most languages. Heroku was acquired by Salesforce.com in 2010 for $212 million.[3]


1. **Node.js** is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications
2. We need to follow the following steps to run the server:
- First of all, we need to create a JavaScript file. Let's name it server.js:

      var http = require("http");

          http.createServer(function(request, response) {
          response.writeHead(200, {"Content-Type": "text/plain"});
          response.write("It's alive!");
            response.end();
          }).listen(3000);

    - The we run the server
            
            node server.js

3. Please follow the link for the rest of the steps, 
[Link](https://howtonode.org/deploy-blog-to-heroku) 
