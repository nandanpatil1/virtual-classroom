# virtual-classroom
this is a full - stack - project 


Tech Stack :

 1) Back-End  - Spring Boot
 2) Front-End - Angular
 3)  Database  - MySQL


Backend (Spring Boot):
 Created,
	1) Models
	2) Repositories
	3) Service Layer
	4) Controllers

 For, Class
      Unit
      Session
      Lecture
      Comment
      Environment
      User

These models use JPA for database mapping, allowing you to store and retrieve this data easily from an SQL database.

Each model has a Repository interface that extends JpaRepository, which provides basic CRUD (Create, Read, Update, Delete) operations for interacting with the database

The Service layer contains the business logic.Services ensure that only the correct data is passed between the repository and the controllers

These controllers accept HTTP requests (GET, POST, PUT, DELETE) from the frontend and provide JSON responses.

I used Code Editor as sts(Spring-tool-suite)

u can use whatever but this project needs to connect to Internet to install dependencies.

Note : Make Changes in Application.proprties file .
       Give ur databse configurations so it will work properly.



Frontend (Angular):

Created,

1) Components
2) Routing
3) Services
4) Data Binding
5) Simple Ui Design

Here i used VS Code,
  First u need to install node & npm
  and hit npm install to install dependency using angular cli and connect it to internet.


  after all done hit ng serve and see in web page.
 





