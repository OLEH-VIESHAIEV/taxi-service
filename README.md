# Simple implementation of Taxi-Service!

3 layers architecture Taxi-Service based on SOLID principles using Servlets and JDBC

## Functionality
-   Add/Delete/ShowAll driver
-   Add/Delete/ShowAll manufacturer
-   Add/Delete/ShowAll car
-   Add driver to car

## Structure
3 layers architecture
- Data access layer: DAO
- Business logic layer: Services
- Presentation layer: Controllers

## Technologies,
- Java
- JDBC + MySQL
- Servlets
- JSP + JSTL
- HTML + CSS
- Apache Tomcat
- Maven
- Custom Injector

## How to run project
1. Clone the project on your IDE
2. Run the script from resources/init_db_my.sql
   Check if you don't have DB named taxi. Else configure init_db_my.sql for yourself
3. In src/main/java/taxi/util/ConnectionUtil replace URL, USERNAME, PASSWORD stubs with your properties.
4. Configure TomCat Local server
   Deploy at server startup "web-security:war exploded", application context "/"
5. Run project!
