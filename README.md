# Taxi-service

### M first project using Java language

- Taxi-service was created to show knowledge of JAVA Core, JDBC, SQL, HTML, SOLID.
- Application has simple registration, authentication and authorization features. Authentication based on HttpSession and filter which does not allow client access the resource. Authorization based on filter with 2 roles (admin, driver).
- Admin allowed to create, delete and see whole list of cars, drivers and manufactures. Admin role can be set in DB.
- Driver role set by default to each user after registration. Driver has access to 2 pages where he can see current car and update his personal information.

### Technologies used

- Java 11
- JDBC
- MySQL
- Java Servlet API
- JSP, JSTL
- Tomcat 9.0.50

### How to deploy

- Fork the project to your repository and use 'Code' to clone into your IDE.
- You must have installed Tomcat or other Servlet container.
- Run script from /resources/init_db.sql to create needed DB.
- Go to /taxi/util/ConnectionUtil.java and change variables values to appropriate data to have connection to your DB and web server.
- Now you can configure your project using a web server and start the app.

### Contact

#### email- [alex.linkoln7391@gmail.com](mailto:alex.linkoln7391@gmail.com)
#### telegram - [@azllar](https://t.me/azllar)