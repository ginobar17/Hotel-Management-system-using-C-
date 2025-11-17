🏨 Hotel Management System (C++ Project)

A console-based Hotel Management System built in C++, implementing core concepts of Object-Oriented Programming (OOP) such as inheritance, polymorphism, classes, file handling, and virtual functions.
The system allows hotel admins to manage rooms, customer check-in/check-out, staff salary calculation, and basic bill generation.

⭐ Features
👤 Customer Module
Collects customer details (name, phone number, age, address)
Aadhaar verification to determine nationality
Automatic customer ID generation
Room booking and availability check
Bill generation based on:
Number of days
Fixed room rate ($100/day)
10% discount for Indian customers
Manual room number selection for customers choosing rooms

🛠 Admin Module
Admin password: 1220
Provides the following functions:

✔ Room Management
View availability of 100 rooms
Check-in customer
Check-out customer
Tracks occupied rooms using internal memory and data.txt

✔ Staff Management
Calculate staff salary based on:
Role (Manager, Receptionist, Cleaner, Security)
Working hours
Monthly working days
Supports overtime pay calculation
Simple role-based salary calculator

🧾 Room Features
Maximum of 100 rooms
Room availability stored in:
room_occupied[] array
data.txt file for persistence
Automatically finds the next available room
Room availability validation before check-in
Proper check-in & check-out flow

💾 File Handling

Uses:
data.txt → Stores occupied room numbers
fstream and ifstream used for reading/writing room data

🧱 Technologies Used
C++
OOP Concepts (Inheritance, Polymorphism, Virtual Functions)
File Handling
Standard Template Library (STL not used, but similar logic implemented manually)
Basic console-based UI

🏗 OOP Concepts Demonstrated
✔ Inheritance
Customer inherits from Person and Verification
Admin inherits from Room

✔ Polymorphism
Virtual details() function in Person

✔ Encapsulation
Protected class members
Getter functions for accessing details

✔ Multiple Inheritance
Customer inherits from Person and Verification

📌 System Flow
1. Main Menu
User chooses:
Customer
Admin

3. Customer Flow
Enter personal details
Aadhaar verification
Choose stay duration
Bill generation
Room booking

4. Admin Flow
Enter admin password
Manage rooms
Check availability
Check-in/out customers
Staff salary module
