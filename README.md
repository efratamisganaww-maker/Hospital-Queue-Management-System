Hospital Queue Management System

Overview

The Hospital Queue Management System is a C++ console-based application designed to manage patient queues in a hospital environment. The system uses a priority queue implemented with a linked list to ensure that patients with more serious medical conditions are served before others.

The application also provides role-based access for receptionists and doctors, allowing different users to perform specific operations based on their responsibilities.

 Features

Receptionist Functions

* Add new patients
* Serve patients based on priority
* Search for patient records
* Update patient information
* Cancel patient appointments
* Save patient data to a file
* Load patient data from a file

 Doctor Functions

* View patient information
* Override patient priority in emergency situations

System Features

* Priority Queue implementation using Linked Lists
* File handling for data persistence
* Login and role-based access control
* Input validation
* Patient record management
* Automatic data saving

 Data Structure Used

The system uses:

* Linked List
* Priority Queue
* Structures (`struct`)
* Dynamic Memory Allocation
* File Handling

Patients are prioritized as follows:

| Priority | Condition       |
| -------- | --------------- |
| 1        | Severe Injury   |
| 2        | Serious Illness |
| 3        | Mild Condition  |

If two patients have the same priority, the patient who arrived first is served first.

 Technologies Used

* C++
* Object-Oriented Programming Concepts
* File Handling
* Linked Lists
* Priority Queues

 File Storage

Patient records are stored in:

Patients.txt

The data is automatically loaded when the program starts and can be saved before exiting.

Sample Login Credentials

Receptionist:

* Username: admin
* Password: 123

Doctor:

* Username: doctor
* Password: 456

 How to Run

1. Compile the source code using a C++ compiler.
2. Run the executable file.
3. Login using the available credentials.
4. Select operations from the menu.

Example:

g++ HospitalQueueSystem.cpp -o HospitalQueueSystem

./HospitalQueueSystem

 Learning Outcomes

This project helped develop skills in:

* Data Structures and Algorithms
* Linked List Implementation
* Priority Queue Management
* File Handling
* User Authentication
* Input Validation
* Software Design and Development

 Future Improvements

* Graphical User Interface (GUI)
* Database Integration (MySQL)
* Multiple User Accounts
* Patient History Tracking
* Appointment Scheduling
* Report Generation

 Author

Efrata Misganaw

Software Engineering Student
