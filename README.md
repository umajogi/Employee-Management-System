# Employee-Management-System
A Java Swing + MySQL desktop application for managing employees with login authentication, CRUD operations, and secure database integration.

A desktop-based **Java Swing + MySQL application** for managing employee records.  
This system allows users to **add new employees, view employee details, and remove employees** from the database using their Employee ID.

---

## 🚀 Tech Stack
- **Java (Swing)** → For building the user interface  
- **MySQL** → For storing employee data  
- **JDBC Connector** → For connecting Java with MySQL  
- **IntelliJ IDEA** → IDE for development  

---

## 🔑 Features
✅ Secure login authentication  
✅ Add new employee records (name, salary, department, etc.)  
✅ View existing employees from the database  
✅ Remove employees using Employee ID  
✅ Prevents SQL Injection with Prepared Statements  

---

Import project into IntelliJ IDEA
Add MySQL JDBC Connector
Download mysql-connector-java-x.x.xx.jar (if not already included)
Add it to your project’s classpath
Setup MySQL Database
Run the following queries in MySQL Workbench or command line:

create database employeemanagement;
use employeemanagement;

create table login(
    username varchar(20),
    password varchar(20)
);

insert into login values('uma','123456789');
insert into login values('mahi','2851047585');

You can extend the schema to include employee details (empid, name, salary, department).
Run the application
Start with Login.java
Use the credentials you inserted in the database (username / yourpassword)


