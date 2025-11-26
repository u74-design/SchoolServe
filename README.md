<img width="1028" height="740" alt="Screenshot 2025-11-26 221220" src="https://github.com/user-attachments/assets/aa9a9392-bfeb-4772-8bff-8d18c4fecaa6" />📘 Student Management System

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
#<img width="1028" height="740" alt="Screenshot 2025-11-26 221220" src="https://github.com/user-attachments/assets/b59f336e-a637-42b8-94f2-e2cd6935c5cc" />

#<img width="1146" height="761" alt="Screenshot 2025-11-26 221236" src="https://github.com/user-attachments/assets/666bb047-02da-428d-99cd-696d18f87114" />

#<img width="1135" height="773" alt="Screenshot 2025-11-26 221246" src="https://github.com/user-attachments/assets/160239fb-1f36-4e6b-9006-96b5ac3c187f" />

#<img width="1919" height="913" alt="Screenshot 2025-11-26 221417" src="https://github.com/user-attachments/assets/862ddd7e-7662-4241-9a6d-ef8b42d1f879" />

#<img width="1390" height="917" alt="Screenshot 2025-11-26 221445" src="https://github.com/user-attachments/assets/4b7ed94c-36f1-44e5-a490-6a345b587b81" />

#<img width="1011" height="820" alt="Screenshot 2025-11-26 221509" src="https://github.com/user-attachments/assets/30e4f3c7-1b72-4ed3-961b-9c190edab63f" />

#<img width="1919" height="1018" alt="Screenshot 2025-11-26 221549" src="https://github.com/user-attachments/assets/316c705f-6388-4f00-918d-1762678917b5" />

#<img width="1917" height="1079" alt="Screenshot 2025-11-26 221605" src="https://github.com/user-attachments/assets/e0158873-cee9-4edb-be5c-8d26a3e80937" />

#<img width="1502" height="699" alt="Screenshot 2025-11-26 221628" src="https://github.com/user-attachments/assets/55bd8010-e02d-400e-9545-352cb0055a5a" />

