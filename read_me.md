STUDENT MANAGEMENT SYSTEM – BACKEND
==================================

A simple backend project using Python and FastAPI to manage students.

TECHNOLOGIES USED
-----------------
- Python, FastAPI, MySQL, SQLAlchemy
- JWT Authentication

FEATURES
--------
ADMIN
- Create student (ID auto-generated, default password 123456)
- View all students
- Search student by ID or name
- Mark Present/Absent
- Delete student

STUDENT
- Login using ID + password
- View details: Name, Age, Department, Salary, Attendance
- Change password

DATABASE
--------
- MySQL database: ems
- Table: users
- ORM: SQLAlchemy

RUN PROJECT
-----------
1. Install: pip install -r requirements.txt
2. Update database.py with your DB credentials
3. Run server: uvicorn main:app --reload
4. Test APIs at: http://127.0.0.1:8000/docs


