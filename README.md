
# Online Security Guards Hiring System

## Project Overview
The **Online Security Guards Hiring System** is a web-based application developed using **PHP** and **MySQLi** for secure and efficient management of security guard hiring services. The system provides users with the ability to request security guard services, track their request status, and allows administrators to manage guard profiles, requests, and generate hiring reports. It includes two key modules: **User Module** and **Admin Module**.

## Project Requirements
- **Project Name**: Online Security Guards Hiring System (Using PHP & MySQLi)
- **Languages Used**:  
  - PHP (Version 5.6, 7.x)
- **Database**:  
  - MySQL 5.x
- **User Interface Design**:  
  - HTML, AJAX, JQUERY, JavaScript
- **Web Browser Compatibility**:  
  - Mozilla Firefox, Google Chrome, Internet Explorer (IE8+), Opera
- **Software Required**:  
  - XAMPP / WAMP / MAMP / LAMP

## Project Modules

### User Module
- **Hiring Form**:  
  Users can fill out an online form to hire security guards, specifying details like type of service, duration, location, etc.
  
- **Request Status**:  
  Users can check the status of their hiring requests (Pending, Accepted, Rejected).

### Admin Module
- **Secure Admin Login**:  
  Admin section is protected by secure authentication.
  
- **Admin Settings**:  
  Admins can update profile details and change their passwords.

- **Dashboard**:  
  The dashboard provides an overview of system metrics including:
  - Listed Security Guards
  - Total Hiring Requests
  - New Requests
  - Accepted Requests
  - Rejected Requests

- **Security Guards Management**:  
  Admins can:
  - Add new guards
  - Edit guard profiles
  - Delete guard records
  
- **Hiring Requests Management**:  
  Admins can:
  - View all, new, accepted, and rejected requests
  - Approve or reject user requests
  
- **Hiring Report**:  
  Admins can generate reports of hiring requests over specific periods.

- **Search Requests**:  
  Admins can search for requests using parameters like booking number, name, and mobile number.

## Features
- **User-friendly interface** for submitting guard hiring requests.
- **Admin control panel** to manage security guards and requests.
- **Efficient search and report generation** for tracking and performance analysis.
- **Secure login and authentication** for data privacy.
- **Cross-browser compatibility** for flexibility and ease of access.

## Installation Instructions

1. **Download and Install XAMPP, WAMP, MAMP, or LAMP**:
   - **XAMPP**: [Download Here](https://www.apachefriends.org/index.html)
   - **WAMP**: [Download Here](http://www.wampserver.com/en/)
   - **MAMP**: [Download Here](https://www.mamp.info/en/)
   - **LAMP**: Install as per your Linux distribution guidelines.

2. **Clone or Download the Project Repository**:
   ```bash
   git clone https://github.com/yourusername/security-guards-hiring-system.git
   ```

3. **Move the Project to Your Server Root Directory**:
   - XAMPP: `C:/xampp/htdocs/`
   - WAMP: `C:/wamp/www/`
   - MAMP: `/Applications/MAMP/htdocs/`
   - LAMP: `/var/www/html/`

4. **Create the Database**:
   - Open **phpMyAdmin** in your browser (usually `http://localhost/phpmyadmin`).
   - Create a new database, e.g., `guards_hiring_db`.
   - Import the provided SQL file (`guards_hiring.sql`) into the new database.

5. **Configure the Project**:
   - Open the project’s configuration file (`config.php`) and update the database credentials:
     ```php
     $host = 'localhost';
     $user = 'root';  // or your MySQL username
     $password = '';  // or your MySQL password
     $dbname = 'guards_hiring_db';  // your database name
     ```

6. **Run the Project**:
   - Open your browser and navigate to `http://localhost/your_project_folder/`.

## License
This project is open-source and available under the [MIT License](LICENSE).


