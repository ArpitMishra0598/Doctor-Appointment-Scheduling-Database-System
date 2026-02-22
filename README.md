# Doctor-Appointment-Scheduling-System

This project demonstrates the implementation of a Doctor Appointment Scheduling System using MySQL Server and MySQL Workbench / Command Line Client.
The system manages doctor availability, patient records, and appointment booking while preventing scheduling conflicts and overbooking.

The project is implemented entirely using SQL commands executed through MySQL.

---

## Objectives :-

* To design a structured relational database system
* To manage doctor availability efficiently
* To prevent appointment conflicts and overbooking
* To maintain data integrity using constraints
* To implement transaction control mechanisms
* To apply advanced SQL concepts

---

## Tools Used :-

* MySQL Server
* MySQL Workbench
* MySQL Command Line Client
* SQL
* PlantUML (for UML Diagrams)

---

## Project Structure :-

### 1. Database Creation

Creation of the main database for managing healthcare appointments.
Contains structured relational tables with proper keys and constraints.

### 2. Doctors Table

Stores doctor details including primary key and specialization information.

### 3. Patients Table

Stores patient information with unique identification and contact details.

### 4. Doctor Availability

Defines available dates, time slots, and maximum patients per day.

### 5. Appointments

Handles appointment booking.
Implements validation logic to ensure availability and prevent overbooking.

### 6. Security & Validation

Implements foreign keys, constraints, transaction control, and privilege management.

---

## How to Execute :-

1. Install MySQL Server on your system.
2. Open MySQL Workbench or MySQL Command Line Client.
3. Log in using your MySQL root password.
4. Create a new database for the project.
5. Select the created database.
6. Execute SQL queries to create all required tables.
7. Insert sample data into doctors and patients tables.
8. Insert availability records.
9. Execute the appointment booking query.
10. Use SELECT queries to verify data integrity.
11. Use SHOW TABLES to confirm successful table creation.

---

## Learning Outcomes

* Understanding relational database design
* Implementation of primary and foreign keys
* Data integrity using constraints
* Transaction control (COMMIT / ROLLBACK)
* Overbooking prevention using SQL logic
* Basic database security using GRANT and REVOKE

---

## Author

Arpit Mishra
SYIT – DBMS Project
Academic Year: 2025–2026
