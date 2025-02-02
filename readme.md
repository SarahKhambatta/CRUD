CRUD Application
This is a simple CRUD application built to manage users. It allows you to create, read, update, and delete user records in a database. The application uses PHP and MySQL for server-side functionality and frontend technologies like HTML, CSS, and JavaScript for a responsive user interface.

Table of Contents
Introduction
Technologies Used
Features
Setup
Usage
License
Introduction
The CRUD Application is a basic web application to demonstrate the fundamental operations of creating, reading, updating, and deleting records from a database. It provides an intuitive interface for managing user data such as name, email, and role.

Technologies Used
Frontend:

HTML
CSS
JavaScript
Backend:

PHP (for server-side scripting)
MySQL (for database management)
Tools:

XAMPP or WAMP (local server environment)
Git (version control)
Features
Create: Add new users to the database.
Read: View user details in a table format.
Update: Modify user information, such as name and email.
Delete: Remove users from the database.
Search: Filter users based on name or email.
Responsive Design: Accessible on mobile and desktop devices.
Setup
To get the CRUD application up and running on your local environment, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/crud-application.git
Set up your database:

Create a MySQL database named crud_app.
Run the provided SQL script (database.sql) to set up the necessary tables.
Configure database connection:

Open the config.php file and update the database credentials:
php
Copy
Edit
$host = 'localhost';
$user = 'root';
$pass = '';
$dbname = 'crud_app';
Start the server:

You can use XAMPP or WAMP to start Apache and MySQL servers on your local machine.
Access the application:

Open your browser and navigate to http://localhost/crud-application.
Usage
Add a new user: Fill out the "Add User" form with the user's name, email, and role, then click "Submit".
View all users: All users will be listed in a table format. You can filter and sort the list as needed.
Edit user details: Click on the "Edit" button next to the user's information to update their details.
Delete a user: Click on the "Delete" button to remove a user from the database.
License
This repository is licensed under the MIT License. See LICENSE for more information.

