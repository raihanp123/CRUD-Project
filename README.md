CRUD PROJECT 

This is the README for my TVShow List Project

Contents:

- External Links
- Specification
- Jira
- Data Structure
- Back-End
- Databases
- Front-End
- Testing
- Future Improvements


External Links - 

Here is a link to my presentation: https://docs.google.com/presentation/d/1t88D9ZMPvAZbVviM5z5stMJBUA4t-nGZOS-90VZCSWc/edit?usp=sharing

Here is a link to my jira board: https://team-1624352285994.atlassian.net/jira/software/projects/PROJ/boards/2

 Specification - 

The Specification of the Project was the following:
To create a CRUD application with the utilisation of supporting tools, methodologies and technologies that encapsulate all core modules covered during training.

The Project involved multiple concepts that I worked on during training. The core modules covered in this Project was the following:

- Project Management
- Databases
- Java SE
- Spring Boot
- Front-End Development
- Automated Testing

 Jira- 

For the planning element of the project I decided to use a Jira board. A Jira Board was used as Jira is a very good tool to create/plan out tasks and set realistic: goals, estimations and difficulty. It also lets you plan out sprints so you can see progress being made on a project.
Jira Board

Here is an image showing an example of my Jira Board:

![jira](https://user-images.githubusercontent.com/86321052/127571919-9cd233df-9512-475b-9dc1-5fd7129f9117.JPG)

As you can see, the jira board is showing the current sprint that was used for the project. it also shows some of the User Stories I used whilst planning out the planning.

 Database Structure - 

After creating the Jira Board the following structure of the project was designed:

- Back-End
- Database
- Testing
- Front-End

Firstly I started out with creating the Back-End coding for the Project which consisted of the Java Element, next databases were implemented where I created a database and linked the Java files to it. After that Testing was initialised on the functionality of the code and finally the front-end software will be written where the webpage will be created.

 Back-End - 
 
The back-end of the project consisted of the elements of the project the User cannot see, it is where the backbone of the project code lies. The first element of code that was created was setting up the initial Java files which consisted of: a general java file (setting up the array and objects for the API), a controller to process the requests for the API (get, put, post and delete).
After that was set up, the service files were written so that the java files can "talk" to the databases and the front-end. Next the Spring Boot files and structure were set up, here the back-end the database was set up an it's path was initialised as well as the port number used for the local server. After that was done the Back-End code was completed.

Databases -

A database was set up which included a table called TVShow_db. This table would receive incoming data and store this in the database. It is very useful to have databases set up when running API's as the data can be stored, without them, the user will have no data each time the server is initialised and will have to create the records again.
Below you can see a screenshot of the My SQL database which includes the TVShow table:

![mysql-multiple](https://user-images.githubusercontent.com/86321052/127572125-2ac906a2-df39-46e9-a775-17b7bd7ba8b6.JPG)

As you can see data is stored in the table which can then be used the next time the server runs.

Front-End - 

The Front-End of the project consisted of: HTML, Javascript and CSS files. The HTMl file sets up the webpage (live server) and allows the user to interact with it, the Java side deals with the actual functionality of the API, here all the functions and variables are set up so that requests can be called. The Javascript included the functionality for all the API requests and allowed the server to request the correct information from the database. Finally the CSS file is used for styling, this sets up the look for the webpage. Another styling method that used was BootStrap which is a CSS framework that allows additional styling to the webpage.

A screenshot of my final result using the front-end functionality can be seen below:
![front-end](https://user-images.githubusercontent.com/86321052/127572180-939bc948-e577-4234-b2d2-1da496c626cd.JPG)
As you can see the web server includes all the functionality to request data from the spring boot server.

Testing -

Whilst coding, multiple tests were carried out to test the functionality of the API. The following testing methods were used:

- Junit
- Integration Testing
- H2 Database

Junit and Integration testing was carried out to test the overall functionality of the API. The testing methods test the functions in each class and the code the behaviour of the code. Testing is also carried out when the Spring Boot Application is running to see if the specified request functions are working.
Below I have attached a screenshot of a successful code run:

![Integration Testing](https://user-images.githubusercontent.com/86321052/127572266-888988a1-7462-412b-a0e8-96e7023b7207.JPG)

The final method of testing was using a H2 database. Here a virtual database is set up to emulate the MySQL database before the actual database is implemented. H2 bases perform the same way as MYSQL and is used to see if server can request and write records in the database. Below I have a picture showing table data inside the h2 database:

![h2 database](https://user-images.githubusercontent.com/86321052/127572311-2a270d4c-a58d-492d-bdf0-9b33c863ec46.JPG)

Future improvements - 

If I had additional time, I would:
- set up functionality for a second table
- add a sort function (e.g. sort by rating or number of episodes)
- Add a warning to the User if they update or delete TVShow records
- Add linkage to a different webpage for each request

Project By Raihan Patel
