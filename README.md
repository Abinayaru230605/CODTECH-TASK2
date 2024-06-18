# CODTECH-TASK2
OBJECTIVE:Create a student management system that can handle student registrations,
maintain student records, and calculate grades. The system should allow adding,
editing, and deleting student information.

 Definition: Student structure holds student details like id, name, marks, and grade.
Global Variables: students array to store student records and student_count to keep track of the number of students.
Function Definitions:
calculateGrade(float marks): Calculates the grade based on the marks.
addStudent(): Adds a new student to the array.
editStudent(): Edits an existing student's details.
deleteStudent(): Deletes a student record by ID.
displayStudents(): Displays the list of students.
Main Function: A loop that provides a menu to perform various operations like adding, editing, deleting, and displaying students.
This program uses a simple array to store student records, which limits the number of students to MAX_STUDENTS. For a more robust solution, consider using dynamic memory allocation or a database.
