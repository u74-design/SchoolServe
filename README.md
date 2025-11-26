📘 Student Management System

The Student Management System is a Full-Stack MEN (MongoDB, Express, Node.js) web application designed to securely manage student academic records.
It uses role-based authentication where teachers have full CRUD control, while students can only view their own details. The system ensures security, organized data storage, and clean UI-based navigation.
🚀 Features
👨‍🏫 Teacher (Admin) Panel
Secure login authentication
Add new student records
Update student details
Delete student data
View full student databas
Session-based authorization
👨‍🎓 Student Panel
Login with unique credentials
View personal details only
Cannot update/delete records
Access restricted to self information
🔐 Authentication & Sessions
express-session for session handling
Middleware to protect routes
Unauthorized users are blocked from access
Teacher and student role permissions handled separately
🗄 Tech Stack Used
Technology	Purpose
Node.js	Backend runtime
Express.js	Server + Routing
MongoDB	Database storage
EJS	Templating engine / UI rendering
Express-Session	Authentication system
HTML / CSS / JS	UI styling and interaction
📂 Database Structure
1. TeacherInfo (Collection)
Field	Type
Name	String
Email	String
Username	String (login ID)
Password	String
2. StudentInfo (Collection)
Field	Type
Name	String
Roll No.	Number
Class	String
Attendance	Number
Marks	Number
Contact/Email	String
Other Student Details	Optional fields
🔄 Workflow
Teacher/Student login
Session validates user role
Teacher controls CRUD operations

Students can only view their profile

Logout ends session and access expires
