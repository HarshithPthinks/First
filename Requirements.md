Problem Statement and Requirements
Goal: Create a program to manage data for 58 students, each with the following properties:
    1. Name:
    • Maximum 30 characters.
    • It should only contain alphabets.
    • It should not contain any numbers or special characters.

    2. USN (University Serial Number):
        ◦ Exactly 10 characters, a combination of letters and numbers.
        ◦ Must be unique for each student.
        ◦ Each of the positions should contain the following format:
			Position 1: Digit 
			Position 2: Uppercase Alphabet 
			Position 3: Uppercase Alphabet 
			Position 4-5: Digits 
			Position 6: Uppercase Alphabet 
			Position 7: Uppercase Alphabet 
			Position 8-10: Digits 
    3. Gender:
        ◦ Single character: either 'M' for  (Male) or 'F' for (Female).
    4. Date of Birth (DOB):
        ◦ Format: dd/mm/yyyy.
    5. Mobile Number:
        ◦ Exactly 10 digits and unique for each student.
Rules:
    • No duplicate USN or mobile numbers.
    • Correct format should be followed for USN, gender, DOB, and mobile number.
    • It should handle invalid inputs and missing information by showing that the input is invalid or the information is missing.
    • All student data must be saved so data is not lost when it is closed.
Program Features
    1. Add a Student:
        ◦ The user should be prompted to enter the student’s USN, name, gender, DOB, and mobile number.
        ◦ It should validate the input, making sure that the USN and mobile number are unique, and store the data.
    2. Delete a Student:
        ◦ The user will enter the USN of the student to be deleted.
        ◦ The system will search for the student by USN, and if found, remove their record.
        ◦ After deletion, the remaining students will be re-organized to maintain continuity.
    3. Display All Students:
        ◦ The system will display the list of all students, showing their USN, name, gender, DOB, and mobile number.
        ◦ If there are no students, it should notify the user that the list is empty.
    4. Update a Student's Information:
        ◦ The user will enter the USN of the student whose information needs to be updated.
        ◦ Once the student is found, the user can modify their name, gender, DOB, or mobile number.
        ◦ It will validate the new data before updating the record.
    5. Exit the Program:
        ◦ The user can choose to exit the program.
        ◦ It will stop accepting input and close the program.


