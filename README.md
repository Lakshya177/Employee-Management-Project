# Employee-Management-Project (Java Swing + JDBC)

## 📌 Introduction 
<pre>
The Employee Management System is a desktop application developed using Java Swing and JDBC. The system helps an organization 
Manage employee records by adding, updating, deleting, and viewing employee details. The system automatically generates Employee 
ID and validates user input data.
</pre>
---

## 🎯 Objectives
<pre>
- To develop a desktop application for managing employee records
- To perform CRUD operations (Create, Read, Update, Delete)
- To store employee data in a database using JDBC
- To provide a user-friendly interface using Java Swing
</pre>
---

## 🛠️ Technologies Used
<pre>
- ☕ Java (Core Java)
- 🖥️ Java Swing
- 🔗 JDBC
- 🗄️ MySQL Database
- 💡 NetBeans IDE
</pre>
---

## ✨ Features
<pre>
-Add Employee
-Auto Generate Employee ID
-Search Employee by ID
-Update Employee Details
-Delete Employee Record
-View All Employees
-Input Validation
</pre>

---

## 🗄️ Database
<pre>
CREATE DATABASE employee_db;
USE employee_db;
CREATE TABLE employee_db (
    emp_id INT PRIMARY KEY AUTO_INCREMENT,
    empName VARCHAR(50) NOT NULL,
    email VARCHAR(50) NOT NULL,
    mobile VARCHAR(10) NOT NULL,
    city VARCHAR(50) NOT NULL
);
</pre>

---

## ✅ Validation Rules
<pre>
-No field should be empty
-Mobile number must be 10 digits
-Email must contain '@' and '.'
-Employee ID is auto-generated
</pre>

---

##  📂 Project Structure
<pre>
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
</pre>

---

## 📷 Screenshots
<pre>
<img width="500" height="444" alt="Screenshot (469)" src="https://github.com/user-attachments/assets/70e398d9-cecd-431a-9493-c522c165e0b1" /> <img width="500" height="444" alt="Screenshot (470)" src="https://github.com/user-attachments/assets/2d5f75d4-3f0b-4956-b457-5b8b7ade3580" /> <img width="500" height="444" alt="Screenshot (471)" src="https://github.com/user-attachments/assets/777090f9-afe7-4340-a611-b8b8ebf4caf8" />  <img width="500" height="444" alt="Screenshot (472)" src="https://github.com/user-attachments/assets/75f3e359-f563-456d-ab5c-dfca132fabbc" />  <img width="500" height="444" alt="Screenshot (473)" src="https://github.com/user-attachments/assets/ce1f70fc-ef43-49dd-8a02-9ba56e1724dc" />
</pre>

---

## 📌 Conclusion
<pre>
The Employee Management System is a desktop application built using Java Swing and JDBC to manage employee records.It performs 
CRUD operations and includes validation for accurate data entry. This project helped in understanding Java GUI, JDBC connectivity, 
and database operations.
</pre>

---

## 👨‍💻 Author

**Lakshya Gupta** 
<pre>
☕ Java Developer  
🖥️ Swing  
🔗 JDBC  
🗄️ MySQL
</pre>
