# Library Management System
This is a desktop-based Library Management System developed using Java (JDK: Java Development Kit), NetBeans IDE (Integrated Development Environment), Swing (Graphical User Interface), and MySQL (Structured Query Language) database. The system allows an admin to manage books and staff information in a library environment.
# Project Idea
The application provides a simple interface for an admin to log in and manage library data. After login, the admin can access a dashboard where books and staff details can be viewed, added, or removed. The system stores information using a MySQL database and performs operations using SQL commands.
 # Main Features
- Admin login
- View, add, and remove books
- View, add, and remove staff
- Edit admin details
# TECHNOLOGIES USED
- Java (JDK)
- NetBeans IDE
- Swing (GUI)
- MySQL Command Prompt
- MySQL Connector (Java Database Connectivity)
# DATABASE SETUP
Run the database_setup.sql file in MySQL Command Prompt to create the database and tables.
The database name used in this project is:
LIBRARY
# DATABASE CONNECTIVITY
Add MySQL Connector to the project libraries in NetBeans:
Project > Properties > Libraries > Add JAR/Folder
Use the standard JDBC connection in the code:
jdbc:mysql://localhost:3306/LIBRARY
# How To Run
1. Install Java JDK and NetBeans IDE
2. Install MySQL and create the database using the provided SQL file
3. Add MySQL Connector to the project libraries
4. Update the database password in the connection code if required
5. Build and run the project in NetBeans
# Sample Login
Username: USERNAME
Password: PASSWORD
