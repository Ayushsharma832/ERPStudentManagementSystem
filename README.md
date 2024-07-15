
# ERP System for Institution

This C++ program implements an ERP (Enterprise Resource Planning) system for educational institutions. It allows users to manage student records, including adding new students, displaying all records, removing students, editing student information, and searching for students based on registration number, name, or branch.


## Features

- **Add New Student:** Input student details such as name, branch, and roll number.

- **Display All Students:** View a sorted list of all student records.

- **Remove Student:** Delete a student record based on registration number.

- **Edit Student:** Modify student information by entering new data.

- **Search Student:** Search for a student by registration number, name, or branch.
## Usage

#### 1. Add New Student:

- Choose option 1 to add a new student.
- Enter the student's name, branch, and roll number.
#### 2. Display All Students:

- Choose option 2 to display all student records.
- View the list of students sorted by registration number.
#### 3. Remove Student:

- Choose option 3 to remove a student.
- Enter the registration number of the student to be deleted.
#### 4. Edit Student:

- Choose option 4 to edit student information.
- Enter the registration number of the student to be edited.
- Input the new data for the student.
#### 5. Search Student:

- Choose option 5 to search for a student.
- Select the search criteria (registration number, name, or branch).
- Enter the relevant details for the chosen criteria.
#### 6. Exit:

- Choose option 0 to exit the program.
## File Handling

- Student records are stored in a file named "College.txt."
- The program reads existing records from the file at the beginning and writes back the updated records when exiting.
## Note

- The program uses bubblesort for sorting student records based on registration number.
- Avoid using spaces in names or branches as they may lead to unexpected behavior.