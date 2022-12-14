# :taxi: Taxi service :taxi:
___
## :bulb: ***Project description***

    A simple version of the taxi service web-application.

## :scroll: ***Project structure***

    The project has an N-Tier Architecture.

+ *Dao* - all the work with the database takes place at this level;
+ *Service* - is responsible for the business logic of the application;
+ *Controller* - allows to user to work with this application.

## :exclamation: ***Features***

+ *Log in / Log out*
+ *Registration*
+ *Car manipulations*
    + display all cars
    + add new car
    + delete car
    + add driver to car
+ *Manufacturer manipulations*
    + display all manufacturers
    + add new manufacturer
    + delete manufacturer
+ *Driver manipulations*
    + display all drivers
    + add driver
    + delete driver
    + display cars for current driver

## :books: ***Technologies***

+ *Java 11*
+ *MySql*
+ *JDBC*
+ *Maven*
+ *Tomcat*
+ *JSP*

## :desktop_computer: ***Quickstart***

1. Fork this repository
2. Copy link of project
3. Create new project from Version Control
4. Set the necessary parameters in ConnectionUtil.class
```java
    private static final String URL = "URL";
    private static final String USERNAME = "USERNAME"; 
    private static final String PASSWORD = "PASSWORD";
    private static final String JDBC_DRIVER = "JDBC_DRIVER";
```
5. Run script in your database from file init_db.sql
6. Install Tomcat
7. Add Tomcat server to configuration and Fix it
8. Run project

![Taxi](https://user-images.githubusercontent.com/24671785/192152852-a056d387-c6ab-485c-ac24-e0faf391569a.gif)
