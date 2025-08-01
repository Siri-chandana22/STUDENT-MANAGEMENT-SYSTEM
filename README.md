# STUDENT-MANAGEMENT-SYSTEM

# DESCRIPTION:

**Library Imports and Dependencies:**

The project begins by importing standard Python libraries like:
Tkinter for building the graphical user interface (GUI),
SQLite for the database backend,
CSV for exporting data,
and Datetime to handle date-specific operations like attendance logging.

**Database Setup:**

An SQLite database named students.db is created (or connected to if it already exists). Two tables are defined:
students: Holds the core student information like name, roll number, email, course, gender, date of birth, attendance count, and grade.
attendance_log: Tracks each instance of attendance marking by storing student ID and date.

**Login Screen:**

A simple login screen ensures that only authorized users can access the system. It requires a predefined username and password. Upon successful login, the main application window is launched. Incorrect login credentials trigger an error message.

**Main Application Interface:**

After logging in, the main application window appears. It contains input fields, buttons, and a tabular data view using TreeView. Users can interact with the system to manage student records.

**Add Student Functionality:**

The application allows administrators to enter new student data through form fields. On clicking the "Add Student" button, the input is validated and then stored in the database. The display table updates to reflect the new entry.

**Displaying Student Data:**

All student records are fetched from the database and displayed in a table using the TreeView widget. Each row represents one student with details like ID, name, roll number, and more.

**Attendance Management:**

Users can select a student and increase their attendance count by one with a button click. This also logs the attendance date in a separate table, helping maintain a detailed history.

**Grade Update Feature:**

The admin can update the grade for any selected student by entering a grade in a text field and clicking the “Update Grade” button. The grade is saved to the database and displayed immediately.

**Delete Student Records:**

The system allows deletion of student records. This removes the student’s data from both the student table and the attendance log to keep the database clean and consistent.

**Search Student by Roll Number:**

Users can search for a student using their roll number. If a match is found, only that student's details are shown in the table. This helps in quickly locating individual student data.

**Export to CSV:**

All student data can be exported to a CSV file. The user selects a location to save the file. This feature is useful for backups or analysis in external tools like Excel.

**User Interface Elements:**

The UI is cleanly designed with:
Labels and entry boxes for input,
Buttons for actions like adding, searching, deleting, and exporting,
A TreeView widget for structured data display.

# OUTPUT:

**Login Page:**

![Image](https://github.com/user-attachments/assets/3d2bcf95-a834-4a5b-928a-ff80505e3811)

**Add User:**

![Image](https://github.com/user-attachments/assets/bab8428b-cf1f-4936-a5bc-5088bea238d4) 
![Image](https://github.com/user-attachments/assets/94b282df-4c9b-4baf-9849-6d52a5753b79)

**Search By RollNumber:**

![Image](https://github.com/user-attachments/assets/2b1652e3-0ce1-46dd-ad13-e7e1656dc420)

**Show Student Data:**

![Image](https://github.com/user-attachments/assets/cb3f2c0d-dfaa-4f20-88ad-63aa1c436e6f)

**Delete Student:**

![Image](https://github.com/user-attachments/assets/77720f30-f3af-43b5-a6fc-ddfe463fdd12)

![Image](https://github.com/user-attachments/assets/f76bf365-0533-40a7-8c51-26f45f21b3a5)









