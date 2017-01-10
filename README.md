# Om Nom Midland
Intended to be a test that includes the following:
- Aurelia Framework
- Aurelia Fetch Client
- Sever Side HTTP Requests in node

##Aurelia Framework Test
I come from a durandal + C# Web API 2 background.
I used an MVC controller as a file server that would serve 
the main index.html (index.chtml since it was mvc) 
that would supply the start up for the durandal portion of the app.

##Aurealia Fetch Client
Originally I'm used to the jQuery Ajax library. I have heard that the built in
Fetch client is more performant and more tightly coupled to the current standard.

##Sever Side HTTP Requests in node
Generally speaking, whenever you build an application that has a database,
you're going to have to send information to your API/Backend to interact with it.
What happens if you've built out a bunch of micro-services that aren't hosted on the same origin?
Heck even if you're hosting on the [same domain but have a different port](https://www.w3.org/Security/wiki/Same_Origin_Policy)
the request is now a Cross Origin request and the serving host must be configured to allow CORS.
You can skip around this by pushing your requests to your server side code.
I want to see if I can get a node server up and running hosting the app on the same domain (srever and port).

#Application Requirements
- Request Information from remote APIs regarding Restruants in the Area
- Request Information from remote APIs regarding resurant hours
- Request Infromation from remote APIs regarding restruant menus
- Request Information from remote APIs regarding restruant themes(food they server; ex: Mexcian, American, ect.)

`Note: The API we are currently targeting is the google API`
