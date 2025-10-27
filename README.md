# University Management System

## Overview
Java-based University Management System for Alexandria University.  
Implements Object-Oriented Programming principles to simulate core university operations for students, faculty, and admin staff.

## Features
### User Authentication & Profiles
- Login with username & password
- Different dashboards based on user roles
- Password reset functionality
- Profile management

### Student Management
- Course registration and withdrawal
- GPA calculation and academic records
- View grades and attendance

### Course Management
- Course creation and modification
- Assignment and grade management
- Schedule and enrollment management

### Faculty & Department Management
- Faculty profile management
- Course assignment and performance tracking
- Department structure management

### System Administration
- Manage users and system settings
- Backup and secure data

## OOP Design Principles
- **Inheritance:** Base `User` class with `Student`, `Faculty`, `AdminStaff`, `SystemAdmin` subclasses  
- **Encapsulation:** Private attributes with getters/setters and validation  
- **Polymorphism:** Overridden methods like `calculateGPA()` and `generateReport()`  
- **Abstraction:** Abstract classes and interfaces for common behaviors  
- **Composition & Aggregation:** `Student` has `Enrollment`, `Department` has multiple `Faculty`, `University` coordinates all entities  

## Author
**Nour Mahmoud Abdelmoneim Ahmed Abouelshohud**  
Intelligent Systems Student, Alexandria University  
