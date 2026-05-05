# PHP MySQL Employee Portal

## Overview

This project is a **database-backed web application** built with PHP and MySQL. It simulates a basic employee portal with authentication and course enrollment functionality.

This project demonstrates backend development concepts, database integration, and secure coding practices.


## What This Project Demonstrates

* Backend development using PHP
* Database design and integration with MySQL
* User authentication workflows (registration & login)
* Secure coding practices (password hashing, prepared statements)
* CRUD-style operations (user + enrollment data)
* Full project documentation (SRS, UML, schema)


## Features

* User registration
* Login authentication
* Password hashing
* MySQL database connection
* Course enrollment functionality
* Prepared SQL statements
* Supporting documentation (SRS, UML, screenshots, schema)

## Tech Stack

* PHP
* MySQL
* HTML/CSS
* SQL


## Project Structure

* `index.php` - Landing page
* `register.php` - User registration
* `login.php` - User login
* `enroll.php` - Course enrollment
* `db_connect.php` - Database connection

### Documentation

* `Database_Schema.pdf`
* `UML_Design_Model.pdf`
* `Application_Screenshots.pdf`
* `SRS_EmployeePortal_AmirClark.docx`

## Learning Outcomes

* Built a full-stack PHP/MySQL web application
* Implemented secure authentication systems
* Used prepared statements to prevent SQL injection
* Designed relational database schema
* Created professional software documentation (SRS, UML, etc.)


## Running the Project (Optional)

To run locally on a personal machine:

1. Install XAMPP or MAMP
2. Start Apache and MySQL
3. Place project files inside:

   * `htdocs` (XAMPP) OR
   * `MAMP/htdocs`
4. Create a MySQL database (example: `employee_portal`)
5. Import database schema or create tables manually
6. Update database connection in `db_connect.php`:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "employee_portal";
```

7. Open in browser:

```
http://localhost/employee-portal/index.php
```


## Notes

This repository is intended for **portfolio and demonstration purposes**.
It showcases backend logic, database integration, and application structure.


## Author

Amir Clark
https://www.linkedin.com/in/amir-clark-a7127731b
