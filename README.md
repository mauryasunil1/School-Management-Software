# A School Management Software 

It is demonstrating how to implement simple CRUD operations with a `Product` entity.

## Technologies (IDE) client/server
**#Server
This project is based on the [Spring Boot](http://projects.spring.io/spring-boot/) project use these packages :
- [Neteans IDE](https://netbeans.org/index.html)
* this IDE help us to:
    - Setting Up the Project
    - Adding Code to the Generated Source File
    - Compiling and Running the Application
    - Building and Deploying the Application
    - Next Steps
  To complete this tutorial, you need the following software and resources
- [Maven](https://maven.apache.org/)
    - Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.
- [Spring Core](https://spring.io/projects/spring-boot)
    - it is used to create stand-alone Spring applications and we embe Tomcat, Jetty or Undertow directly (no need to deploy WAR files)
- [Spring Data](https://spring.io/projects/spring-data-jdbc)
    -  it easier to build Spring powered applications that use data access technologies. Since it module deals with enhanced support of JDBC based data access layers
- [Spring MVC](https://www.tutorialspoint.com/spring/spring_web_mvc_framework.htm)
    - THe MVC ( Model-View-Controller) is use to designe the architecture of web applications.
- [Thymleaf](https://www.thymeleaf.org/)
    - Thymeleaf is a modern server-side Java template engine for both web and standalone environments. it help to design and deploy HTML on the browser.
- [JDK](http://java.sun.com/javase/downloads/index.jsp)
    - Which stand for Java Development Kit, which help us to develop, text, protype, and demonstrate JAVA Apps.
 
 
**#Client Side

## Installation 
The project is created with Maven, so you just need to import it to your IDE and build the project to resolve the dependencies

## Database configuration 
Create a MySQL database with the name `springbootdb`and add the credentials to `/resources/application.properties`.  
The default ones are :

```
spring.datasource.url=jdbc:mysql://localhost:3306/springbootdb
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
```

## Usage 
Run the project and head out to [http://localhost:8080](http://localhost:8080)
* Login Page
![loginpage](https://github.com/idrice24/School-Management-Software/blob/master/src/main/resources/static/images/adminlogin.PNG)
