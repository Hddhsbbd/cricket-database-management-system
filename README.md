# Cricket Database Management System

A Java-based desktop application designed to manage cricket-related data such as players, teams, matches, and scores using a MySQL database.  
This project demonstrates the practical application of Database Management Systems concepts integrated with Java.

---

## Objectives
- To design and implement a relational database for cricket data
- To perform CRUD operations using Java and MySQL
- To understand database connectivity using JDBC
- To build a functional desktop-based management system

---

## Technologies Used
- **Programming Language:** Java  
- **UI Framework:** Java Swing  
- **Database:** MySQL  
- **Database Connectivity:** JDBC  
- **Build Tool:** Apache Ant  
- **IDE:** NetBeans  

---

## Features
- Player management (add, update, delete, view)
- Team management
- Match scheduling and score storage
- Date selection using JCalendar
- Persistent data storage using MySQL database
- User-friendly desktop interface

---

## Project Architecture
This project follows a **2-Tier Architecture**:
1. **Presentation Layer:** Java Swing GUI  
2. **Data Layer:** MySQL Database connected using JDBC  

---

## Project Structure
cricket-database-management-system/
│
├── src/ # Java source files
├── nbproject/ # NetBeans project configuration
├── dist/ # Compiled executable JAR file
├── build.xml # Apache Ant build file
├── cricket_database.sql # MySQL database schema
├── mysql-connector-java-8.0.27.jar
├── jcalendar-1.4.jar
└── manifest.mf
