## JS-introduction
Basis curriculum for JS intro 

#Week 1, Class 1: Introduction to JavaScript and Rails review
[TUES] 
JS Introduction (http://www.w3schools.com/js/js_intro.asp)
JS Selections http://learn.jquery.com/using-jquery-core/working-with-selections/
JS-HTML DOM http://www.w3schools.com/js/js_htmldom.asp 

JavaScript Syntax 
(http://www.w3schools.com/js/js_syntax.asp)

Functions 
(http://www.w3schools.com/js/js_functions.asp)

Week 1, Class 2: JavaScript - Making things happen on your page, part II
[THURS] 

Using Arrays to store data 
(http://www.w3schools.com/js/js_arrays.asp) 

Selectors 
(http://api.jquery.com/category/selectors/)

Closure and passing an Object 
(http://javascriptissexy.com/understand-javascript-callback-functions-and-use-them/)

JavaScript Best Practices & other reference 
(http://www.w3schools.com/js/js_best_practices.asp)

Assignment:

Create a single web page that includes at least three forms of "user interaction.” Your code should make use of the following: arrays, selectors & loop/s.

ComprehensiveJS overview: http://chimera.labs.oreilly.com/books/1230000000345/ch03.html#_javascript_gotchas 

#Week 2, Class 1: JQuery and JavaScript, part I
[TUES] 
review the prior week homework assignment 
review JS questions/challenges with loops, selectors, syntax, etc

If conditions: https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Statements/if...else

Using the JS console

DOM Manipulation with javascript
(http://www.w3schools.com/js/js_htmldom.asp)

#Week 2, Class 2
[THURS] 
Class assignment:
Create a trivia game checking an input answer with event listener
Iterate through a an array of foods and render - I love to eat food[i]

Homework reading:

#Week 3, Class 2: JQuery and JavaScript, part II
[THURS] 
  
JS events
(http://www.w3schools.com/js/js_htmldom_document.asp)

Loops 
(http://www.w3schools.com/js/js_loop_for.asp)

Assignment:

TBD

[TUES] Week 4, Class 1: Data Organization & Management, part I


JQuery 
http://learn.jquery.com/about-jquery/how-jquery-works/
http://jquery.com/

JQuery Objects 
https://www.smashingmagazine.com/2014/05/mystery-jquery-object-syntax-basic-introduction/ 

jQuery Events 
http://learn.jquery.com/events/introduction-to-events/

jQuery Documentation 
http://api.jquery.com/


Class Assignment:
Make a todo list that does the following:
User can enter a task to a list via input field
Once a task is created, user can remove a task
Once a task is create, user can mark task as done


[THURS] Week 4, Class 2: Data Organization & Management, part II


Basic underscore
https://github.com/craigprotzel/Mashups/blob/master/05_Dealing_With_Data/Basic_Underscore/friends.js

Regular Expressions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions
Change order of an input string
Use special characters to verify input
Advanced searching with flags


Assignment

(TBD) 


[THURS] Week 5, Class 1: Back to the Server, part I

review the prior week homework assignment
review any JQuery Objects, Events or Listeners questions or challenges

Overview of Node express framework 
http://www.nodebeginner.org/

Download Node express framework here:
http://expressjs.com/

Explain Node express routes
http://modernweb.com/2014/04/07/the-basics-of-express-routes/ 


Homework reading:

Tutorial on moustache.js
http://coenraets.org/blog/2011/12/tutorial-html-templates-with-mustache-js/

Try handlebars.js
 http://tryhandlebarsjs.com/ 


[THURS] Week 5, Class 2: Back to the server, part II


NPM dependencies 
https://docs.npmjs.com/files/package.json#dependencies

Creating HTML templates with Mustache.js
https://www.sitepoint.com/creating-html-templates-with-mustachejs/

Handlebars.js in 10 minutes
http://tutorialzine.com/2015/01/learn-handlebars-in-10-minutes/


Assignment

Create a Node-Express app that runs locally on your computer that has 4 routes
'/' - the landing page
'/:term' - a page with an api request based on the url
'/api/:term' - a page that shows json data based on the url
'*' - a catch all page


[TUES] Week 6, Class 1: MVCs with JavaScript, part I

review the prior week homework assignment
review the node / node express framework & routes

What are JavaScript MVCs? (and code examples)
http://alistapart.com/article/javascript-mvc 

Visual MVC map for newbies
http://code.tutsplus.com/tutorials/mvc-for-noobs--net-10488


Homework reading

Questions to ask about MVCs
http://stackoverflow.com/questions/386885/is-there-a-javascript-mvc-micro-framework



[THURS] Week 6, Class 2: MV*s with JavaScript, part II


Code examples (side-by-side) with backbone.js, Ember.js and Angular.js
https://www.codementor.io/javascript/tutorial/angular-vs-ember-vs-backbone-beginners-learn


Assignment

(TBD)

This will be based on the concept of a Single-Page Applications (SPA), and how JavaScript MVC frameworks help you build a SPA. 

Reference map: https://www.codementor.io/javascript/tutorial/should-you-build-your-web-application-with-javascript-mvc-frameworks 

[TUES] Week 7, Class 1: Storage with Couch DB

review the prior week homework assignment 
review node /node express function, commands, usage questions & challenges

CouchDB how-to
http://guide.couchdb.org/editions/1/en/tour.html

CouchDB in 15 minutes
http://wiki.apache.org/couchdb/CouchIn15Minutes 

Cloudant overview & basics
https://docs.cloudant.com/basics.html


Homework reading:

CouchDB Technical Overview http://docs.couchdb.org/en/1.6.1/intro/overview.html


[THURS] Week 7, Class 2: Couch DB (Server-side notepad built with CouchDB)

Sign up for Cloudant
Sign in to Cloudant and create a new database, 
Save the name of the new database as the value for `CLOUDANT_DATABASE` in app.js.
Also in app.js, save your Cloudant username as the value for `CLOUDANT_USERNAME`.
Back in Cloudant, when viewing your new database, choose the "Permissions" Option.
Click "Generate API Key" and take the KEY and PASSWORD values and save them in app.js as `CLOUDANT_KEY` and `CLOUDANT_PASSWORD`.. **This is your only chance to see the Password**.
Then, from the permissions page in Cloudant, check the **Reader** and **Writer** boxes for the KEY you just created.
In Terminal, `cd` into this main directory and run `npm install`.
Be sure there were no errors with the previous step. If not, then run: `npm run start` or `node app.js`
Now visit [http://localhost:3000/](http://localhost:3000/) and you've got a notepad synced to a couchdb account.

Assignment: Create a Node-Express app that runs locally on your computer and saves data to CouchDB (on Cloudant). 

Your app should include the following:
ability for user input to be saved in your database
presentation of data from your database on a page
At least one route that serves data from your database to a page as json

[TUES] Week 8, Class 1: JavaScript creative visualisation

review the prior week homework assignment 
review CouchDB usage question and setup

Download P5
http://p5js.org/download/
 
Overview of P5JS
https://github.com/processing/p5.js/wiki/p5.js-overview
 
Intro P5 tutorial
http://p5js.org/get-started/
http://p5js.org/


Homework reading:


*Video* - Object Oriented JavaScript (27mins): https://www.youtube.com/watch?v=PMfcsYzj-9M
 
Object-Oriented JavaScript: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript
 
What is ‘this’ in JavaScript: https://www.sitepoint.com/what-is-this-in-javascript/



[THURS] Week 8, Class 2: JavaScript media libraries


Visualisation with ChartJS
http://www.chartjs.org/docs/#getting-started-creating-a-chart 



Assignment:

(TBD - add more specifics)

Create a single web page experience that displays one type of data in chart form using ChartJS. The project must be deployed on the world wide web.




[TUES] Week 9, Class 1: All About APIs, week one (Instagram)

review the prior week homework assignment 
review questions/challenges with using P5JS or ChartJS library elements 

Using APIs in JavaScript 
http://www.poynter.org/2011/how-to-use-apis-from-google-facebook-twitter-to-find-data-ideas/141786/

Modifying API examples 
https://gigaom.com/2010/10/29/using-apis-not-quite-as-hard-as-it-looks/


Homework reading:

What are APIs http://readwrite.com/2013/09/19/api-defined/ 
Instagram API https://www.instagram.com/developer/



[THURS] Week 9, Class 2: All About APIs 


Modifying the Instagram API 
https://github.com/robynitp/networkedmedia/wiki/Instagram-API-How-to 


Assignment: 

Create a single web page that, upon user input, responds with data from the Instagram web API. One approach to this assignment could be to design the page around answering a question for the user. An example of this is www.doineedanumbrella.com

Remember:
(1) a user needs to "trigger" an event
(2) data needs to be requested via AJAX from the APIs, and 
(3) the page should update appropriately. 

 Your completed assignment should include a .html file, a .css file, and a .js file.


[TUES] Week 10, Class 1: All About APIs I (Google Maps)

review the prior week homework assignment 
review questions/challenges with using Instagram API data

Simplified http client (Request)
https://github.com/request/request


Homework reading:

Modifying API examples https://gigaom.com/2010/10/29/using-apis-not-quite-as-hard-as-it-looks/ 

Google Maps API http://www.w3schools.com/googleapi/google_maps_basic.asp



[THURS] Week 10, Class 2: All About APIs II 


Practice API data calls with the Google Maps API 
https://developers.google.com/maps/documentation/javascript/


Assignment: 

Create a single web page that, upon user input, responds with data from at least 2 web APIs. Remember:

(1) a user needs to "trigger" an event
(2) data needs to be requested via AJAX from two APIs, and 
(3) the page should update appropriately. 

Your completed assignment should include a .html file, a .css file, and a .js file.


[TUES] Week 11, Class 1: Authorization (server-side)

review the prior week homework assignment 
review API commands, usage questions & challenges

Basic authentication
https://en.wikipedia.org/wiki/Basic_access_authentication

Node basic authentication
https://github.com/jshttp/basic-auth

Base64 - decode & encode (brief explanation)
https://www.base64decode.org/


Homework reading:

Open Authentication, explained: https://hueniverse.com/oauth/guide/intro/
OAuth with Foursquare, explained: https://www.sitepoint.com/oauth-explained-with-foursquar/


[THURS] Week 11, Class 2:  Server-side open authorization / OAuth

Passport JS Authentication for node
http://passportjs.org/

Twitter OAuth
https://dev.twitter.com/overview/documentation


Assignment:

(TBD)


[TUES] Week 12, Class 1: Client-side authorization

review the prior week homework assignment 
review authorization questions & challenges

ClientSide Auth with Hello.js
http://adodson.com/hello.js/


Homework reading: 

(TBD)


[THURS] Week 12, Class 2: Client-side authorization

(TBD)


Assignment:

(TBD)


