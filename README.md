# PHP MySQL Employee Portal

## Overview
This project is a database-backed employee portal web application built with PHP and MySQL. It includes user registration, login authentication, course enrollment functionality, and database connectivity.

## Features
- User registration
- Login authentication
- Password hashing
- MySQL database connection
- Course enrollment functionality
- Prepared SQL statements
- Supporting SRS, UML, screenshots, and database schema documentation

## Tech Stack
- PHP
- MySQL
- HTML/CSS
- SQL

## Project Files
- `index.php` - Landing page
- `register.php` - User registration
- `login.php` - User login
- `enroll.php` - Course enrollment
- `db_connect.php` - Database connection
- `Database_Schema.pdf` - Database schema documentation
- `UML_Design_Model.pdf` - UML design model
- `Application_Screenshots.pdf` - Application screenshots
- `SRS_EmployeePortal_AmirClark.docx` - Software Requirements Specification

## Learning Outcomes
- Built a PHP/MySQL web application
- Implemented user authentication and database-backed functionality
- Practiced secure coding concepts such as password hashing and prepared statements
- Created supporting software engineering documentation including SRS, UML, screenshots, and schema design

## Setup Instructions

1. Install XAMPP or MAMP (for local PHP/MySQL environment)

2. Start Apache and MySQL

3. Place project files inside:
   - htdocs (XAMPP) OR
   - MAMP/htdocs

4. Create a MySQL database (example: employee_portal)

5. Import database schema using provided SQL or create tables manually

6. Update database connection in `db_connect.php`:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "employee_portal";


## Author
Amir Clark  (www.linkedin.com/in/amir-clark-a7127731b)  
