# Taxi-Service App
![](https://t4.ftcdn.net/jpg/01/93/82/25/360_F_193822519_45xqEMvxEpF8X3Wbqdr0dBK1jkXwQwrK.jpg)





This project is an imitation of working taxi service app with:
- creating, displaying and deleting manufacturers, cars and drivers after user's authentication
- assigning drivers to cars and displaying available cars for currently authorized user


#  Project Description

This Project is based on SOLID principles using Servlets and JDBC as well as on 3-layered architecture, such as:

- Data access layer (DAO)

- Application layer (service)

- Presentation layer (controllers)

## System requirements

- IntelliJ IDEA Ultimate IDEA
- JAVA 11+
- Web-server (Apache Tomcat);
- Database (MySQL);
- Maven

## Configure you env

-  First, make sure your env meets requirements listed above
-  Then clone project on your IDE and run the script from resources/init_db_my.sql in MySQL for creating DB
-  In src/main/java/taxi/util/ConnectionUtil change URL, USERNAME and PASSWORD with your data
-  Configure TomCat Local server