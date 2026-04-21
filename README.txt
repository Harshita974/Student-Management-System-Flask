Project: Student Management System (Task 3 Completion)

1. Project Overview
This is a Full-Stack Student Management System built using Flask and SQLite. This version completes Task 3 by implementing full CRUD (Create, Read, Update, Delete) functionality for managing student records.

2. Features (CRUD Flow)
- Create: Users can add new student records (Name, Email, Course) via the 'Add Student' form.
- Read: All stored student data is fetched from the database and displayed in the 'Registered Students' table.
- Update: Records can be modified using the 'Edit' feature, which pre-fills the form with existing student details.
- Delete: Users can remove records from the database, including a confirmation prompt for safety.

3. Technologies Used
- Backend: Python (Flask)
- Frontend: HTML5, CSS3, Jinja2 Templates
- Database: SQLite3

4. How to Run
- Ensure 'database.db' is in the project folder.
- Run the application: python app.py
- Access the site at: http://127.0.0.1:5000

5. Testing Credentials
- Username: InternUser
- Password: [The password you remember]

6. Security Note
Session management is active; unauthorized users are redirected to the login page if they attempt to access student management routes directly.
