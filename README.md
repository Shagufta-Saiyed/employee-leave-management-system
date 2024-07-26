# employee-leave-management-system
The Employee Leave Management System is a web application designed to manage employee leave requests efficiently. It provides a user-friendly interface for employees to submit leave requests and for administrators to manage and approve these requests.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: XAMPP
- **IDE**: Visual Studio Code

## Features
- Employee login and registration
- Submit leave requests
- View leave status
- Admin dashboard to manage leave requests
  
## Installation and Setup
### Prerequisites
- XAMPP
- Visual Studio Code
- Web browser (Chrome, Firefox, etc.)


### Steps to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shagufta-saiyed/employee-leave-management-system.git

Move the project to the XAMPP htdocs directory:

-Copy code
>mv employee-leave-management-system /path-to-xampp/htdocs/
>Start XAMPP:

-Open the XAMPP Control Panel.
>Start the Apache and MySQL modules.
>Create the database:

-Open phpMyAdmin by navigating to http://localhost/phpmyadmin.
>Create a new database named elms.
>Import the provided SQL file (elms.sql) to set up the necessary tables and data:
>In phpMyAdmin, select the elms database.
>Click on the Import tab.
>Choose the elms.sql file from your project directory and click Go.
>Configure the database connection:

-Open config.php or the respective configuration file in your project.
>Update the database connection details as needed:
php
Copy code
$servername = "localhost";
$username = "root";
$password = ""; // Default is empty for XAMPP
$dbname = "elms";


Run the project:

Open a web browser and navigate to http://localhost/employee-leave-management-system.
You should see the application’s login page.
