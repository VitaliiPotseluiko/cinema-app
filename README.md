# Cinema-App
This application implements a cinema service model with the ability to register and authenticate user, control access to various data. Booking service based on Hibernate and Spring frameworks using general REST principles.

# Features
- it takes to login before using
- every user has roles: `USER` and `ADMIN`
  - with Andmin role you can:
      - register new users
      - see all users
      - can add and get movies
      - can add and get cinema hall
      - can add, update, delete and get movie session
  - with User role you can:
      - register new users
      - add session to his own shopping cart and get it shopping cart
      - complete him order and get him orders history
      - get movies
      - get cinema hall
      - get movie session
# Model structure
![](https://github.com/VitaliiPotseluiko/hibernate-shopping-cart-hw/blob/master/Hibernate_Cinema_Uml.png)

# Technologies
- **Java** `v.17.0.3.1`
- **Maven** `v.3.8.7`
- **Spring** `v.5.3.20`
- **Spring Security** `v.5.6.10`
- **Hibernate** `v.5.6.14.Final`
- **MySql** `v.8.0.22`
- **Java Servlets** `v.4.0.1`
- **Jackson core** `v.2.14.1`
- **Javax annotation** `v.1.3.2`
- **Tomcat** `v.9.0.65`
