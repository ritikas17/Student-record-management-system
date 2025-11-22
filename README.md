# Student record managementt system
The overview of the project is can be used by educational institutions to maintain their student records easily. Achieving this objective is difficult using the manual system as the information is scattered, can be redundant, and collecting relevant information may be very time-consuming. All these problems are solved by this project.This system helps in maintaining the information of pupils of the organization. It can be easily accessed by the manager and kept safe for a long period of time without any changes.
\n
The code employs a class named `Student` to encapsulate the essential attributes and methods associated with a student. This class encompasses functions to determine the percentage and grade of a student, acquire and showcase student data, and perform file operations for the storage and retrieval of student records. The primary program comprises a loop that offers users a menu, enabling them to navigate through diverse functionalities.
**Hardware Requirements:** Standard personal computer or laptop.
**Software Requirements:** Python interpreter must be installed on the system.
Student Class: The core functionality is implemented in the `Student` class, which serves as a blueprint for creating student objects with specific attributes such as roll number, name, and subject marks.
Binary Data Handling: The `struct` library is employed for working with binary data. This facilitates the serialization and deserialization of `Student` objects, ensuring efficient storage and retrieval when reading and writing to a file.
File Operations: The system utilizes file operations to manage student records. It writes and reads binary data to and from a file named "student.dat."
