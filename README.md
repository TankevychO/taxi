<<<<<<< HEAD
# taxi
=======
# taxi
>>>>>>> origin/main
#  🚖 **Taxi service**
The application describes the operation of the taxi service. </br>
To implement the application were created: </br>
- taxi_service database
- models: Car, Driver, Manufacturer
- interfaces DAO and implements for each model
- interfaces "Services" and implements for each model and authentication
- logger in the AuthenticationService
- filter for authentication driver
- controllers for all actions
#### Performs the following actions:
![This is an image](http://joxi.ru/krDdxkETGEJe6r.jpg)
#### _These functions are available after registration. An unregistered user goes to the login form and has the opportunity to register._</br>
________________________________________________________________________________________________________________________
#### Technologies:
- JDBC
- MySQL(v 8.0.22)
- Apache Tomcat (v 9.0.55)
- Servlet(v 4.0.1)
- Maven
- JSTL(v 1.2)
- Logger(v 2.14.1)
- HTML, CSS
- JSP
_______________________________________________________________________________________________________________________
#### Implementation details and technologies
Project based on 3-layer architecture:</br>
![This is an image](https://progi.pro/media/main/f5/f0/11/f5f01101de396d5c76a8eb66efaf9653.png)
_______________________________________________________________________________________________________________________
#### Setup "Taxi service"
- [x] Install MySQL and MySQL Workbench
- [x] Configure Apache Tomcat
- [x] In `pom.xml` change to the absolute path         
  `PATH TO checkstyle.xml`
  ![This is an image](http://joxi.ru/DmB6xRGcqwgkxm.jpg)
- [x] In `log4j2.xml` change to the absolute path
  `PATH TO app.log`
  ![This is an image](http://joxi.ru/zANxkBLU1B8okm.jpg)
- [x] Run script from the resources/init_db.sql file in the Workbench.
- [x] In `/util/ConnectionUtil.java` change
  `URL`, `USERNAME`, `PASSWORD`, `JDBC_DRIVER`
  ![This is an image](http://joxi.ru/bmoavbwsOx7qPA.jpg)
