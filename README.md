Employee Database App – Java JDBC

Build a Java application that connects to a MySQL/PostgreSQL database and performs full CRUD operations (Create, Read, Update, Delete) on an employee table using JDBC.

Tools & Technologies

Java
IntelliJ Community Edition
MySQL Workbench
JDBC Driver
Project Structure

Employee Database App

DBConnection.java - Handles DB connection and contains CRUD logic
README.md - Project documentation
Setup Instructions

Database Setup mysql workbench

CREATE DATABASE employee;

CREATE TABLE employee_details ( id INT PRIMARY KEY AUTO_INCREMENT, name VARCHAR(100), dept VARCHAR(50), salary DOUBLE );

Add JDBC Driver

Download MySQL Connector/J from MySQL Downloads (The Jar file I have used - mysql-connector-j-9.4.0)

Add the JAR to your project classpath.

Run the App

Compile and run emp.java

Use the menu to add, view, update, or delete employee records.

Key Concepts Covered

JDBC Connection
PreparedStatement vs Statement
SQL Exception Handling
DriverManager, ResultSet, Auto-commit
Sample Output

DB Connected successfully!

--- Employee Database App ---

Add Employee

View All Employees

Update Employee

Delete Employee

Exit

Enter choice:


Snapshot:-
<img width="1920" height="1080" alt="Screenshot (283)" src="https://github.com/user-attachments/assets/012fc5fa-91d0-446b-b84b-e1247916ec66" />

<img width="1920" height="1080" alt="Screenshot (282)" src="https://github.com/user-attachments/assets/66953e04-3184-4490-94bc-1b2fa3b376db" />

<img width="1920" height="1080" alt="Screenshot (280)" src="https://github.com/user-attachments/assets/e3d478a5-1006-4b7d-b9d8-30a62abefd44" />
Author:- Tarang katiyar



