# Python projects

# Project-1
## Three buttons for start, stop, reset by using tinter it should be a an GUI application

* It is a simple GUI application using the Tkinter library in python. This application has three buttons
  for start, stop and reset along with a timer label.
* The timer starts when you click the start button,paues when you click the stop button and resets to 0
  when you click the reset button.

# Project-2
## CALCULATOR: Using tinter create a GUI application of calculator using grid

* It is a simple calculator GUI application using Tkinter with a Grid layout. Its create a simple calculator
  application with a grid layout using Tkinter.
* You should see a calculator GUI with buttons arranged in a grid layout.

# Project-3
## FORM CREATION  Using tkinter in that email validation should be done using regular expression during submit if email is valid it should be submitted if not it should be showing form failed to submitted

* A simple form using Tkinter in python. The form includes an email entry and when the user clicks the submit button,
  it checks if the entered email is valid using a regular expression, if the email is valid a message is displayed
  otherwise a message indicating a failed submission is shown.
* The email validation is done using a basic regular expression pattern. You can customize the regular expression to
  to fit your specific requirements for email validation.
* If the email is valid, a success message is displayed otherwise an error message is shown.
  
# Project-4
## School Management System:
* a. teacher - tables - sno,teacherId ,teacherName, teacherSalary, teacherJoiningDate
* b. students - tables - sno,studentId ,studentName, pythonMark,MathMark,PhysicsMark
        * create a students
   		  * read a students 
   		  * update a students
   		  * delete a student
* c. principal - tables - sno,teacherId ,teacherName, teacherSalary, teacherJoiningDate
* d. admin - table - sno,adminId,adminName, adminPassword
* admin who can able to create a teacher,students,principal,admin

## Steps:
1. Import Necessary Libraries
2. Connect to the PostgreSQL Database
3. Create Tables
4. Define CRUD Functions
5. Create Admin

* Here, I import the psycopg2 library, which is a PostgreSQL adapter for Python, and the sql module from psycopg2 for constructing SQL queries.
* This code establishes a connection to the PostgreSQL database using the provided connection parameters.
* Similar CREATE TABLE statements are executed for the 'students', 'principal', and 'admin' tables. These statements define the structure of the tables.
* Here, I created a student, read the list of students, update a student, read again, delete a student, read again, and finally, create an admin.


