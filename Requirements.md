Software Requirements for Student Management System
 1. Student Data Storage
	The system must store details for 58 students, with every student having these 	information:
        ◦ Name
        ◦ USN (exactly 10 characters)
        ◦ Gender ('M' for Male or 'F' for Female)
        ◦ Date of Birth (DD/MM/YYYY format)
        ◦ Mobile Number (Exactly 10 digits)

2.Rules 
    • The system should make sure that no two students have the same USN.
    •  Data should be in correct format (ex: 10-character USN, correct gender format, etc.).
    • The system should handle incorrect input or missing information.
    • All student information should be saved to make sure that the data is not lost when 	the system is closed.  
    • It should be easy-to-use.

3. Features
[1] Adding a Student
When you choose to add a student:
    • The system will prompt you to enter the student's ID, name, age, grade and mobile number.
    • This information is stored in memory (for example, in an array or a list of students).
    • Each student will have a unique ID to differentiate them from others.
[2] Deleting a Student
When you want to delete a student:
    • The system will ask for the ID of the student you want to remove.
    • It will search through the list of students to find a match.
    • If the student with the given ID is found, their record will be deleted by removing their entry from the list.
    • The remaining student records will shift to fill the gap left by the deleted student.
[3] Displaying Students
When you choose to display students:
    • The system will show a list of all students currently stored.
    • For each student, it will display their ID, name, age, and grade.
    • If there are no students in the system, it will notify you that the list is empty.
[4] Updating a Student
When you want to update a student's information:
    • The system will ask for the ID of the student you wish to update.
    • It will search the list to find the student with the matching ID.
    • Once found, it will prompt you to enter new details such as the student's name, age, or grade.
    • The student’s information will be updated with the new data you provide.
[5] Exiting the Program
When you choose to exit:
    • The system will stop accepting input and close the program.
    • Before exiting, it can optionally save the data to a file, so that any updates or added students are not lost when you reopen the program.