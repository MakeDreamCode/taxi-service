# Taxi Service Application.
## _The app is written for educational purposes and is a simplified taxi service._

## Features
The application has such functions as:
- Register or login as a taxi driver.
- Add new drivers, cars and manufacturers.
- View information about drivers, cars, manufacturers, which car is registered to the driver.
- Add new drivers, cars and manufacturers.
- Register driver in different cars.
- Remove drivers from DB.

## Technologies used:
- Java
- JDBC, MySql
- Servlets, Tomcat
- JSP, JSTL
- CSS, HTML
- Apache, Maven

## Setup
Configure Apache Tomcat.

Install MySQL and MySQL Workbench.

Create a schema and all the necessary tables by using the script 
from resources/init_db.sql in MySQL Workbench.

In the taxi/util/ConnectionUtil.java class change the "USER", "PASSWORD",
"URL", "JDBC_DRIVER" properties to the ones you specified when installing MySQL.

Start the application.