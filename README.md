# User_Management_Web_Application_CURD_Operation
This is a user management web application that allows you to perform CRUD (Create, Read, Update, Delete) operations. The application is built using Java, MySQL, JSP, and Servlet API.

## Features
Create a new user
Read a list of users
Update user details
Delete a user
## Tech Stack
Backend: Java, Servlet API
Frontend: JSP, BOOTSTRAP
Database: MySQL

## Prerequisites
Java Development Kit (JDK)
Apache Tomcat or any other Java EE server
MySQL Server
## Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/user-management-app.git
cd user-management-app
Set up the database:

Open your MySQL client and create a new database:

sql
Copy code
CREATE DATABASE user_management_db;
Navigate to the database directory and import the SQL file to create the necessary tables:

sql
Copy code
USE demo;
SOURCE path_to_sql_file.sql;
Configure the backend:

Open the project in your preferred IDE (e.g. Eclipse).

Update the database configuration in db.properties file:

properties
Copy code
db.url=jdbc:mysql://localhost:3306/demo
db.username=root
db.password=yourpassword
## Deploy the application:

Build the project using your IDE:

bash
Copy code
mvn clean install
Deploy the WAR file to your Apache Tomcat server.

## Run the server:

Start your Apache Tomcat server.
Access the application:

Open your web browser and navigate to http://localhost:8081/demo
Usage
Create a new user:

## Navigate to the "Create User" page.
Fill out the form with the user's details.
Click "Submit" to add the user to the database.
Read the list of users:

## Navigate to the "User List" page.
View the list of all users in the database.
Update user details:

## Navigate to the "User List" page.
Click on the "Edit" button next to the user you want to update.
Modify the user's details in the form.
Click "Update" to save the changes.
Delete a user:

## Navigate to the "User List" page.
Click on the "Delete" button next to the user you want to remove.
Confirm the deletion.
Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss changes.


