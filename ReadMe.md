📚 School Management System (Frontend LocalStorage Version)
📌 Overview

This project is a School Management System implemented using HTML, CSS, and JavaScript.
It provides three separate portals:

👨‍🎓 Student Portal

👨‍🏫 Teacher Portal

👨‍💼 Admin Portal

The system stores all data locally in the browser using LocalStorage, so no backend or database is required.

✨ Features
👨‍💼 Admin Portal

Secure admin login

Add and delete students

Edit marks for all students

View system statistics

Export student data to JSON

Import student data from JSON

Clear all stored data

👨‍🏫 Teacher Portal

Teacher login with predefined credentials

Edit student marks for assigned classes

View class timetable

Class performance dashboard

👨‍🎓 Student Portal

Student self-registration

Secure login

View personal marks

Automatic total, average, and pass/fail status

Change password functionality

🧱 Project Structure
School-Management-System/
│
├── Admin.html      → Admin Portal
├── Teacher.html    → Teacher Portal
├── Student.html    → Student Portal
└── README.md
⚙️ Technologies Used

HTML5

CSS3

JavaScript (Vanilla)

Browser LocalStorage (for persistence)

🚀 How to Run
Method 1 — Direct Open

Download all three HTML files.

Place them in the same folder.

Double-click any file or open in browser.

Recommended start order:

Open Admin.html

Add students

Enter marks

Use Teacher / Student portals

🔑 Default Credentials
Admin
Password: admin123
Teacher
ID	Password	Name
T001	pass123	Mr. Smith
T002	pass456	Ms. Johnson
T003	pass789	Mr. Brown
Student

Students must register using:

Username

Password

Roll number

Class
(Must match admin-created record)

💾 Data Storage

All system data is stored in browser LocalStorage:

studentDatabase → Student list + marks

studentAccounts → Student login accounts

⚠️ Clearing browser data will erase system data.

🔒 Security Notes

This is a client-side demo system

No encryption or backend validation

Not suitable for production use

Intended for learning / demo purposes

📈 Possible Improvements

Backend database (MongoDB / MySQL)

Authentication API

Role-based access control

Cloud deployment

Mobile responsive UI

Chart visualization

Attendance module

👨‍💻 Author

School Management System — Frontend LocalStorage Implementation
