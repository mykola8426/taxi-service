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

### 👽 Technologies used:
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
1. Clone this project to your environment:
   1. Copy reference of this code;
   2. In your environment find 'File->new->Project from version control'.
   3. Paste url.
   4. Press 'clone'.
2. Create schema and tables in Workbench(Instruction in init_db.sql file).
   1. Copy all from 'init_db.sql' file in resources directory.
   2. Open Workbench.
   3. Enter to your connection.
   4. Find 'File -> New Query Tab' or Press 'Ctrl + T'.
   5. Paste copied information.
   6. Press 'Execute'.
3. Write login and password to your db into fields login and password in ConnectionUtil class
4. Add Tomcat Server configure:
   1. Press 'edit configuration' near run button.
   2. Select the plus in the upper left corner.
   3. Find Tomcat Server and choose local.
   4. Press fix button in lower right corner.
   5. Choose 'taxi-service:war exploded'.
   6. Click 'apply' and 'Ok'.
5. Run Tomcat (Press 'run' or 'debug' button).
