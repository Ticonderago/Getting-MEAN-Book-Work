# Nathan Reinhardt Getting MEAN Project
## Chapter 9
Link - https://mysterious-stream-60696.herokuapp.com/
![Screenshot](Chapter9GettingMean.png)

In Chapter 9 it was all about setting up the app_client folder which now held our new
home controller with our services and filters. This is a change from Chapter 8 because
now all the functions are now in their own files. It is a good way of keeping your
function away from other functions so it is more organized and easier to find them. The
chapter went by pretty well, didn't run into to much debugging.

## Chapter 8
Link - https://mysterious-stream-60696.herokuapp.com/
![Screenshot](Chapter8GettingMean.png)

In Chapter 8 the hardcoded code has now been replaced with the angular framework.  This
chapter went really smmooth until the very end. I had only one error and it never threw
the error, but apparently my layout.jade file had a part I missed that was mentioned in
at the start of the chapter. There was never an error thrown, but the webpage it self
while testing only showed the keywords that would hold the data instead of the data it
self from the server.

1. The code on the front-end framework is executed on the client side.
2. Putting a console.log() statement in the AngularJS controller code will give the output
   from console in the browser under the development tools.

## Chapter 7
Link - https://mysterious-stream-60696.herokuapp.com/
![Screenshot](Chapter7GettingMean.png)

In Chapter 7 the goal was to take out all the hard-coded information from the app
and then use the database for the information for the website. Also to test the methods
created in the last chapter. The hard part in this chapter was not noticing that the path
to the add my review page was not being used properly. Needed to add the object id into
the locationid: position.  Everything else in the chapter went really smoothly.

1. This chapter is now "consuming" the REST API that was created within chapter 6. All
the location information is now being fed into the website from the database.
2. When testing out the API lookup error, using the lng or lat as examples of values
to make invalid to test the errors.
3. Javascript interprets lng or lat values of 0 as false.

## Chapter 6
Link - https://mysterious-stream-60696.herokuapp.com/
![Screenshot](Chapter6p2GettingMean.png)
![Screenshot](Chapter6p1GettingMean.png)

In Chapter 6 the book went into how to use api with html and json. This chapter setup
the skeleton for the active live database commands. The commands are there but they
don't interact with everything yet. I had trouble trying to figure out how postman and
my database connected. After finally seeing how they connected then I was able to
understand how the commands on postman worked. Everything else in the chapter worked
well for me. Just the postman connection learning took a bit.

1. When the function locationCreate gets called the services recieve a request at
   /api/locations
2. Making a request to an api is in JSON data format returned from the server.
3. Postman is used for testing an api which sends http requests and functions.
   Useful for receiving requests. Different from web browsers because it can do more
   commands than just simple web browsers.

## Chapter 5
Link - https://mysterious-stream-60696.herokuapp.com/
![Screenshot](Chapter5v2GettingMean.png)

In Chapter 5 the book went into how to set up a local and live database for the website.
It was pretty fun having a ton of console windows open performing different actions while
creating the databases.  The hardest part for me was getting my dumped data pushed up to the
live database. I had the right credentials for the data, but I kept getting Authentication
Errors which meant either my databse host was typed wrong or the username and password could
have been wrong. Went through each one at a time to see which one gave the error. I got it
randomly entering the same information, so it could have been a one off error while typing.
Now the database has been set.

1. Database entries in MongoDB are called documents.
2. The difference between mongod and mongo are huge. mongod runs the database in the
   background in the machine, while mongo is the shell that allows you access to work with
   mongod.
3. Heroku needs MLab to access our live database for Heroku. We can only run it locally
   without MLab.

## Chapter 4
Link - https://mysterious-stream-60696.herokuapp.com/
![Screenshot](Chapter4GettingMean.png)

In Chapter 4, the website is now starting to have proper formatting. After finishing
Chapter 4, I have built a better understanding on how a website can be formatted
and getting really familiar with .jade files. The most challenging part was debugging
the .jade files. The debugging most of the time came down to indentation errors.
In the book on page 99, there is a small error. It shows location-info.js instead of
the correct location-info.jade (listing 4.7). The error can crash the page since it
is the wrong file type. This chapter also went in depth in the controllers and views folders.
Created multiple views for new pages to navigate to.

1. This layout allows to have mixin code that gets called. A mixin is a function that can
   be called through out the code.
2. The location page routes to location-info.jade in the views folder. This file calls the
   outputRating function which is stored in includes. This is called a mixin.
3. Express provides the routing functionality. This is front end functionality.

## Chapter 3
Link - https://mysterious-stream-60696.herokuapp.com/
![Screenshot](Chapter3GettingMean.png)

In Chapter 3 we have a very basic setup for a webpage.  Most of this chapter taught
the basics of using these new tools given at our disposal. Challenges that I had was
making sure app_server was being set correctly cause I remember seting it correctly
at first, but for some reason it didnt save those changes so my bootstrap was not giving
off the proper theme. Seting everything up on a new device is probably the most
challenging concept to do well.

1. This process is called routing. The code that connects a URL request to the controller code
   is called route.
2. When you want to add an external module you use the command npm install.
3. It appears in the console screen.
