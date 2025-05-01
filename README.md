# Student Data Entry System
Description
A Java-based application for managing student data, allowing users to add, update, delete, and view student records stored in a MySQL database.

Features
Add new students.

Update existing student details.

Delete student records.

Search for students by PRN, name, or ID.

Display all students in the database.

Prerequisites
Java 8 or higher.

MySQL database.

CREATE TABLE students (
    ->     id INT AUTO_INCREMENT PRIMARY KEY,
    ->     prn VARCHAR(20) NOT NULL UNIQUE,
    ->     name VARCHAR(100),
    ->     age INT
    -> );

JDBC driver for MySQL (mysql-connector-java).
