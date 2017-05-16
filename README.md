
# Portfolio

This page represents some of the work I did at the Software Guild. The projects below are all coded using C# and ASP.NET MVC on the backend. 

At the Guild, we were continually refactoring as we learned new skills: we started with console apps, moved to Model I web apps, then to Model II web apps, then learned how to connect our apps to a local databases we built in SQL-Server. 

These projects represent just a portion of the work I did at the Guild, and some of the projects represent solo work, some were developed with a pairing partner, and our final project was an individual effort. These details are noted below along with a link to the source code. 

Lastly, we did not learn deployment, so I have been working through deployment on my own. 

----------


  [Multi-Calculator Basic Web App](http://multicalculator-guildwork.rhcloud.com/) 

> This was the first MVC web app I built. I refactored a bunch of calculators that I originally developed as console apps and combined them into a web app with a basic front end.  All work on this project is mine. 
> 
> Here is the [source code](https://bitbucket.org/maere/multicalculatorapp) for the web app.

> (Note: The loan amortization got messed up when I refactored and this needs to be fixed. But here is a [link to the original console app source](https://bitbucket.org/maere/loaninterestcalculator) which actually outputs the correct calculations!)


----------


 [Flooring Master Console App](https://bitbucket.org/maere/flooringmastery) 

> This is a console-based order processing app that persists its data to a text file.  Since this was designed to run in the console, it has no front end currently, but you can view the source code from the link below. 
> 
> This project was done with a pairing partner, and our biggest challenges on this project (as neophyte coders) were:
> 
> -  deciding on the data structures we should use
> - deciding when and where we needed to instantiate our data structures
> - how the classes should relate to each other and how the application should be constructed
> - making sure all of our unit tests passed after each refactoring iteration
> 
> We learned a lot!
> 
> Here is the [code.](https://bitbucket.org/maere/flooringmastery)
> 


----------


 [Address Book App](http://addressbook-guildwork.rhcloud.com/) 

> This is a basic address book application that allows you to add someone's street address and phone number to a live back-end database. Strangely, it has no field for an email address (this was not a requirement). For this reason, my pairing partner and I decided to make it a "vintage" address book.   (Entertaining ourselves with irony.) We used Bootstrap for the layout.
> 
> This app was a really fun one to work on, as my pairing partner was hilarious. So we managed to learn a lot and have fun at the same time. That is actually my ideal work environment. 
> 
> Here is the [code](https://github.com/maere/addressbooklocal) for the project. You can see a palimpsest of sorts in the comments where previous iterations of the code were commented out as the code was refactored from a console app, to a Spring servlet app using JSTL, to an Ajax app (in-memory), to its final database implementation. 
> 
> Note:  Our search implementation uses lambdas, and when I went to deploy the app, I found out that Java 1.8 was not supported by the cloud host. So since lambdas only work in Java 8 the search function will need to be refactored to work in this particular deployment environment, or we will need to redeploy on another server to show that functionality.  You can look for it in the source code though.


----------


 [Car Dealership App] (http://car-dealership-app.apphb.com/)
 
> This application was developed as a solo project and we were given about a week. The goal of the project was to create models a simplified version of a car dealership’s website and sales support system.  Like many car dealership sites this application provides a public-facing area which allows users to browse the inventory of new and used vehicles, view current specials, and contact the dealership.  Additionally, for sales personnel there is an area for logging customer information for a purchase and an administrative area for user management, application management, inventory management, and reporting.
> 
> **Planning:**
> To prepare for collaborative work on a more complex application we developed planning documents that included a UML diagram, [wireframes,](https://github.com/mikechowdiv/CarDealerShip/blob/master/Wireframes.pdf) and a [database schema](https://github.com/mikechowdiv/CarDealerShip/tree/master/sql). 
> 
> **Building:**
> I created a multi-tier MVC application on the back-end, Entity Framework for the DB implementation, ASP.NET MVC 5 project with Web API enabled for the UI Layer.  The app provides basic CRUD functionality, and AJAX and jQuery to populate the respective page.  
> 
> **Project Management:**
> The project management on an individual project like this was not as challenging as a group project, since I didn't have to spend the time on communicating, merging, etc. But it had to be done within a week so it was another kind of challenge. But I got a basic implementation of the project finished, and will continue to implement the remaining features over time.
> 
> Here is [code](https://github.com/mikechowdiv/CarDealerShip) as it is in it's current state.


----------


These apps represent some of my initial forays using C# to code  the backend and middle tiers, as well as working in the full stack with Ajax and jQuery.  
