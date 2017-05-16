
# Portfolio

This page represents some of the work I did at the Software Guild. The projects below are all coded using C# and ASP.NET MVC on the backend. 

At the Guild, we were continually refactoring as we learned new skills: we started with console apps, moved to Model I web apps, then to Model II web apps, then learned how to connect our apps to a local databases we built in SQL-Server. 

These projects represent just a portion of the work I did at the Guild, and some of the projects represent solo work, some were developed with a pairing partner, and our final project was an individual effort. These details are noted below along with a link to the source code. 

Lastly, we did not learn deployment, so I have been working through deployment on my own. 

----------


  [DVD Library Database & Web API](https://github.com/mikechowdiv/DvdLibrary/) 

> This was a web app I built using database objects and interacting with them using the C# database access techniques of ADO.NET and Dapper.  The frontend was done using HTML/CSS/Javascript and the database interaction through an ASP.NET Web API project.
> 
> Here is the [source code](https://github.com/mikechowdiv/DvdLibrary) for the web app.




----------


 [Flooring Company](https://github.com/mikechowdiv/swg/tree/master/Flooring) 

> This is a console-based order processing app that persists its data to a text file.  Since this was designed to run in the console, it has no front end currently, but you can view the source code from the link below. 
> 
> This project was done individually, and the biggest challenges on this project were:
> 
> - deciding on the data structures
> - deciding when and where to instantiate the data structures
> - how the classes should relate to each other and how the application should be constructed
> - making sure all of the unit tests passed after each refactoring iteration
> 
> We learned a lot!
> 
> Here is the [code.](https://github.com/mikechowdiv/swg/tree/master/Flooringy)
> 


----------


 [Shack-Up App](http://shack-app.apphb.com/) 

> This application was to create a a site, "Shack Up!" which allows people to list their shacks on their properties for people to express interest in to rent. Like an AirBNB for people who like to rough it in shacks.
> 
> **Planning:**
> We started our table creation script and use the provided wireframes to intuit a relational design.
>
> **Building:**
> We put together the homepage by developing a responsive design UI, using the Factory Pattern to get the appropriate data, using @model to get the data from our controller into the webpage. Then we built a Web API so we could use AJAX to add a Contact and test it using PostMan. We implemented Dynamic Search, Server Side Validations, and Update Account page.
> For the database, we created stored procedure to delete and reload sample data. We then created a listings repository which used ADO.NET.
>
> **Project Management:**
> Within the team we dicussed how Test Driven Development can be used to write our update test before we implement the code in our repository. We discussed the advantage behind using IEnumerable in our interfaces, learned that sometimes you have to update your unit tests as you continue to add functionality. We explored how now to not write SQL in our C#, and then go through how to properly create these queries. 
>
> Here is the [code](https://github.com/mikechowdiv/ShackApp) for the project. 
> 
> 


----------


 [Car Dealership App](http://car-dealership-app.apphb.com/)
 
> This application was developed as a solo project and we were given about a week. The goal of the project was to create models a simplified version of a car dealership’s website and sales support system.  Like many car dealership sites this application provides a public-facing area which allows users to browse the inventory of new and used vehicles, view current specials, and contact the dealership.  Additionally, for sales personnel there is an area for logging customer information for a purchase and an administrative area for user management, application management, inventory management, and reporting.
> 
> **Planning:**
> To prepare for the work on a more complex application I developed planning documents that included a UML diagram, [wireframes,](https://github.com/mikechowdiv/CarDealerShip/blob/master/Wireframes.pdf) and a [database schema](https://github.com/mikechowdiv/CarDealerShip/tree/master/sql). 
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
