# Student record management system
The overview of the project is can be used by educational institutions to maintain their student records easily. Achieving this objective is difficult using the manual system as the information is scattered, can be redundant, and collecting relevant information may be very time-consuming. All these problems are solved by this project.This system helps in maintaining the information of pupils of the organization. It can be easily accessed by the manager and kept safe for a long period of time without any changes.

The code employs a class named `Student` to encapsulate the essential attributes and methods associated with a student. This class encompasses functions to determine the percentage and grade of a student, acquire and showcase student data, and perform file operations for the storage and retrieval of student records. The primary program comprises a loop that offers users a menu, enabling them to navigate through diverse functionalities.

**Hardware Requirements:** Standard personal computer or laptop.

**Software Requirements:** Python interpreter must be installed on the system.

In this project two modules are imported - struct and os

Struct module is used to ensure the specific datatypes for the respective data entries.These data entries can be comprised of either student academic report,personal information or any other deleted information.

Os module is used to add,update and delete students information in their respective table path where they have been stored in the database.

Student Class: The core functionality is implemented in the `Student` class, which serves as a blueprint for creating student objects with specific attributes such as roll number, name, and subject marks.

Binary Data Handling: The `struct` library is employed for working with binary data. This facilitates the serialization and deserialization of `Student` objects, ensuring efficient storage and retrieval when reading and writing to a file.

File Operations: The system utilizes file operations to manage student records. It writes and reads binary data to and from a file named "student.dat."

# Steps to install and run the project
1) To install the required libraries mentioned in requirement.txt file on your system if not installed already
2) To create a folder in the system and save the cse project.py
3) To open any python interpretor like IDLE,VS Code or PyCharm
4) To open the terminal in the directory where the code file/folder has been saved and run the following command,'python3 cse_project.py'

# Instruction for testing
To ensure that the Student Record Management System functions correctly, follow the steps below to test all its features systematically:

1) Launch the Program
 • Run the project using the command:
python3 cse_project.py
 • Ensure the main menu is displayed with available options (e.g., Add Student, Display Student, Search, Update, Delete, Exit).

2) Test Student Record Creation
 • Choose the Entry/Edit option.
 • Choose create student record.
 • Enter valid inputs for roll number, name, and subject marks.

Verify:
 • The system accepts the data without errors.
 
3) Test Viewing All Student Records
 • Choose the Display Students option.

Verify :
 • All existing records are displayed in a readable format.
 • No incorrect or corrupted data appears.
 
4) Test Searching for a Student
 • Select the Search Student option.
 • Enter a valid roll number.
 
Verify:
 • The system retrieves and displays the correct student record.
 • Searching with an invalid roll number returns an appropriate message (e.g., Record not found).
 
5) Test Updating a Student Record
 • Choose the Modify Student option.
 • Enter a roll number of an existing student.
 • Modify one or more fields such as name or marks.

Verify:
 • The updated data is correctly saved.
 • Re-display or search for the student to confirm the update.

6) Test Deleting a Student Record
 • Select the Delete Student option.
 • Enter the roll number of the student you want to delete.

Verify:
 • The student record is removed from the system.
 • The file reflects the updated list.
 • Searching for the same roll number shows that the record no longer exists.

7) Test Data Persistence
 • Exit the program and relaunch it.
 • Display or search students again.

Verify:
 • All previously added records remain intact.
 • There is no data loss after closing and reopening the program.

8) Test Error Handling
 • Check for proper system behavior when:
 • Entering invalid input (non-numeric marks or roll number).
 • Leaving required fields empty.
 • Trying to update or delete a non-existing record.
 • The system should handle such cases gracefully without crashing.

9) Test Menu Navigation
 • Navigate through all menu options.

Verify:
 • The user interface responds correctly.
 • The loop continues until the Exit option is chosen.
 • No unnecessary program termination or errors occur.
