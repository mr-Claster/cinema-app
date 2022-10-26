# ****CINEMA-APP****
___
## Description
This is simple simulator of cinema service for reservation tickets, that supports registration, authentication and CRUD operations

## Features
- Login/Logout
- Registration
- Set User or Admin roles
- Different opportunities for roles:
  - Admin features:
    - adding new movies, cinema-halls, movie-sessions
    - update/remove information about movie-sessions
    - get all cinema halls, movies, available movie-sessions
    - find user by email
  - User features:
    - complete the order
    - add tickets to the shopping cart
    - get all movies, cinema halls, available movie-sessions



## Technologies
- Java 11
- Maven
- MySQL
- Tomcat
- Hibernate
- Spring

## Quickstart
1. Fork my repository
2. Copy link of project
3. Edit db.properties file
4. Edit resources/db.properties - set the necessary parameters
```properties
    db.driver=YOUR_DRIVER
    db.url=YOUR_URL
    db.user=YOUR_USERNAME
    db.password=YOUR_PASSWORD
```
Example: 
```properties
    db.driver=com.mysql.cj.jdbc.Driver
    db.url=jdbc:mysql://localhost:3306/ticket_app?serverTimezone=UTC
    db.user=root
    db.password=1234
```
5. Install Tomcat
6. Add Tomcat server to configuration
7. Run project

