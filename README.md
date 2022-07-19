![photo of logo](taxiservicelogo.jpg)
# Taxi service
___

### 📒 Project description:
___
    A simple web-application that supports authentication, registration and other CRUD operations.
###  🔗 Features:
___
* registration like a driver;
* authentication like a driver;
* create/update/remove a manufacturer;
* create/update/remove a car;
* create/update/remove a driver;
* display list of all manufacturers;
* display list of all cars;
* display list of all drivers;
* display list of all drivers of the selected car;

### 🖥 Technologies used:
___
* JDK 11
* Maven 3.8.6
* JDBC 
* Servlet API 4.0.1
* MySql 8.0.22
* JSP
* JSTL 1.2

### 🚀  How to run:
___
To correctly use this service you have to install MySQL and Apache Tomcat version 9.
1. Clone this project to your environment:
2. Use /resources/init_db.sql for creating schema and tables
3. Write login and password to your db into fields login and password in /util/ConnectionUtil.java class
4. Add Tomcat Server configure:
   * Press 'edit configuration' near run button.
   * Select the plus in the upper left corner.
   * Find Tomcat Server and choose local.
   * Press fix button in lower right corner.
   * Choose 'taxi-service:war exploded'.
   * Click 'apply' and 'Ok'.
5. Run Tomcat (Press 'run' or 'debug' button).
6. Go ahead and use it!
