🏆 Savion Sports Club Management System

A complete Sports Club Management System built using PHP, MySQL, HTML, CSS, and JavaScript.
It provides role-based access for Admins, Coaches, and Students, enabling efficient management of membership, equipment inventory, borrowing requests, schedules, notifications, and user activity logs.
This system improves operational efficiency, reduces manual tracking, and delivers a clean, user-friendly web interface.

🚀 Features
👨‍💼 Admin Module

Manage users (students & coaches)

Add and update sports equipment

Track equipment availability & condition

Approve/reject equipment requests

Monitor overdue and returned items

Send notifications & announcements

View complete activity logs

Role-based permissions

🏅 Coach Module

Update personal profile

Request sports equipment

View request status

Receive notifications

Track equipment assigned

🎯 Student Module

Register & log in securely

View available sports equipment

Request equipment with return dates

Track request history

Receive updates & reminders

🛠️ Technologies Used

Frontend: HTML5, CSS3, JavaScript

Backend: PHP

Database: MySQL (database.sql)

Server: Apache (XAMPP/WAMP/LAMP)

Security: Password hashing using password_hash()

Other: Bootstrap, FontAwesome (if included)

🗄️ Database Structure (Based on Your SQL)
Table Name	Description
users	Stores admin, coach, and student accounts (role-based)
equipment	Sports equipment details, stock, condition, images
equipment_requests	Borrow/return requests for equipment
notifications	System notifications for users
activity_log	Tracks user actions (audit trail)
🔑 Default Admin Credentials
Username: admin
Password: password


(from your SQL file)

📂 Typical Folder Structure
/assets          -> CSS, JS, Images
/index.php       -> Home page
/login.php       -> Login page
/register.php    -> Registration selection
/register_coach.php
/register_student.php
/logout.php
/equipment/      -> Equipment management pages
/requests/       -> Equipment request system
/admin/          -> Admin-only features
/database.sql    -> SQL database file

⚙️ Installation Guide
1️⃣ Requirements

XAMPP / WAMP / LAMP

PHP 7+

MySQL 5.7+

2️⃣ Setup Steps

Clone or download this repository

Copy the project into your server root:

htdocs/   (XAMPP)
www/      (WAMP)


Import database.sql into MySQL:

CREATE DATABASE savion_sports_club;
USE savion_sports_club;
-- Import SQL file


Update database credentials in your PHP config file (if present)

Start Apache & MySQL

Run the project:

http://localhost/Savion_Sports_Club/

📌 Key Functional Highlights

Secure user roles: Admin / Coach / Student

Inventory control with detailed status tracking

Borrow–return equipment system

Automatic notifications: overdue, low stock, approval updates

Complete audit logs for accountability

Modern structured MySQL database

🤝 Contributing

Contributions are welcome!
Please open an issue or submit a pull request.

📄 License

This project is open-source for educational usage.
