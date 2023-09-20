
# WeCare

WeCare, built in Java and employing the MVC architecture, efficiently handles hospital operations. It separates into Model (data and logic), View (user interface), and Controller (input handling), offering a modular and user-friendly solution for tasks like patient management, appointment scheduling, admin controls etc.

* For front-end of the project, I have used Java Server Pages(JSP) (which acts as the View of the project in the MVC architecture) and also used Bootstrap for designing the Navigation bar and the Footer.

* The server side programming is done using Servlet which acts as the Controller in the MVC architecture.

* I have used MySQL database and used the JDBC driver mysql-connector to connect to the database and perform the CRUD(Create, Read, Update & Delete) operations in the com.db package and the queries for the same has been written in com.dao package and both these packages acts as a Model for the project in the MVC architecture.

* All the dependies are included in the pom.xml file in the root folder.









## Features

There are 6 different packages used to seperate the code based on the MVC architecture.

#### 1. admin/servlet - 
It provides the logic for Adding the Doctor, Adding the Specialist, Admin Login, Admin Logout, Delete the Doctor and Update the details about the Doctor.

#### 2. doctor/servlet -
It provides the logic for Doctor Login, Doctor Logout, Changing the Password, Edit his/her profile, Update the Status regarding to a particular patient.

#### 3. user/servlet -
It provides the logic for taking the Appointment under a particular Doctor, User Login, User Logout, User Register, Change Password.

#### 4. entity -
The contructor and various getter/setter methods are defined in the entity package under the specific entity.

#### 5. db -
It contains the DBConnect file in which the logic for connecting the application to the database is written.

#### 6. dao -
All the queries required for the CRUD operation is written in the dao package under the specific entity.