# To-do-FullStack-Application
Features
User Registration & Login (Authentication)
Create, Read, Update, Delete (CRUD) tasks
Mark tasks as completed
Persistent data storage using MySQL
RESTful API integration
Clean and responsive user interface
Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL
Server Environment: XAMPP
API: RESTful APIs
Project Structure (Example)
/project-folder
│── /assets
│── /css
│── /js
│── /api
│── /includes
│── index.php
│── login.php
│── register.php
│── dashboard.php
│── database.sql
Getting Started (Run Locally with XAMPP)

Follow these steps to run the project on your local machine:

1. Install XAMPP
Download and install XAMPP from the official website
Open XAMPP Control Panel
2. Start Services
Start Apache
Start MySQL
3. Move Project Files
Copy your project folder into:
C:\xampp\htdocs\
4. Set Up the Database
Open your browser and go to:
http://localhost/phpmyadmin
Create a new database (e.g., todo_app)
Import the provided database.sql file:
Click on the database
Go to Import tab
Upload and run the SQL file
5. Configure Database Connection
Open your PHP config/connection file (e.g., config.php)
Update credentials if needed:
$host = "localhost";
$user = "root";
$password = "";
$database = "todo_app";
6. Run the Application
Open your browser and go to:
http://localhost/project-folder
Usage
Register a new account
Log in with your credentials
Add and manage your tasks
Update or delete tasks as needed
Purpose of the Project

This project demonstrates:

Full-stack web development using PHP and MySQL
Building and consuming APIs
User authentication and session management
CRUD operations and database integration
Responsive frontend design using core web technologies
License

This project is open-source and available for learning and educational purposes.
