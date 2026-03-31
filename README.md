# Employee-Management-Project (Java Swing + JDBC)

## 📌 Introduction
The Employee Management System is a desktop application developed using Java Swing and JDBC. The system helps an organization manage employee records by adding, updating, deleting, and viewing employee details. The system automatically generates Employee ID and validates user input data.

---

## 🎯 Objectives
- To develop a desktop application for managing employee records
- To perform CRUD operations (Create, Read, Update, Delete)
- To store employee data in a database using JDBC
- To provide a user-friendly interface using Java Swing

---

## 🛠️ Technologies Used
-Java (Core Java)
-Java Swing
-JDBC
-MySQL Database
-NetBeans 

---

## ✨ Features
-Add Employee
-Auto Generate Employee ID
-Search Employee by ID
-Update Employee Details
-Delete Employee Record
-View All Employees
-Input Validation

---

## 🗄️ Database
CREATE DATABASE employee_db;
USE employee_db;
CREATE TABLE employee (
    emp_id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50) NOT NULL,
    mobile VARCHAR(10) NOT NULL,
    email VARCHAR(50) NOT NULL,
    department VARCHAR(50) NOT NULL,
    salary DOUBLE NOT NULL
);

---

##  📂 Project Structure
Employee_Management_Project
│
├── Source Packages
│     └── default package
│            ├── Employee_form.java      (Main JFrame - Dashboard)
│            ├── Registration.java       (Add Employee JFrame)
│            ├── ShowAll.java            (Show All Employee JFrame)
│            ├── Search.java             (Search Employee JFrame)
│            ├── Update.java             (Update Employee JFrame)
│            ├── Delete.java             (Delete Employee JFrame)
│            ├── DBConnection.java       (Database Connection)
│            ├── Employee.java           (Model Class)
│            ├── EmployeeDAO.java        (JDBC CRUD Operations)
│            └── Validation.java         (Validation Code)
│
├── Libraries
│     ├── JDK
│     └── MySQL Connector Jar
│
├── Test Packages
│     └── (Optional – can create for testing)
│            └── EmployeeTest.java
│
└── Test Libraries


---

## 📷 Screenshots
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2287d1c5-3d08-4d80-b927-d7ebe0ad2058" />


---

## 📌 Conclusion
The Employee Management System simplifies the process of managing employee records. It provides an efficient way to store, retrieve, and manage employee data using Java Swing and JDBC. The system reduces manual work and improves data management in an organization.

---

## 👨‍💻 Author
Lakshya Gupta
