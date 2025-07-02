# Library-Management-System

This library management system in C++ keeps track of which students have borrowed, given out, returned, and are still owning books. C++’s library management system is written in C++
Before entering the main system, users must log in as students or librarians.

To get access to the Librarian’s account, a password should be provided for the Librarian only.
There are many features in this system. The user can also change the password from the system for their security.

ABOUT PROJECT	PROJECT DETAILS
Project Name :	Library Management System
Project Platform :	C/C++
Programming Language Used:	C++ Programming Language
Developer Name :	Aryan Rathaur
IDE Tool (Recommended):	Dev-C++/Codeblocks
Project Type :	Desktop Application
Database:	Stores data in .DAT file

# What is a Library Management System?
The Library Management System, as its name suggests, is a piece of software that manages all of the library’s data.
Instead of recording information in a notebook, it makes the job of the librarian relatively simple.
In the past, librarians recorded book information in notebooks along with the names of the students who had borrowed each book. Therefore, it was extremely challenging to keep track of every book.
If a librarian wanted to look for a specific book, that task took a lot of time. Therefore, computer languages like C++ were created to make this work easier.

# How the Library Management System Works?
The technology automates fundamental library tasks to support a librarian’s day-to-day activities. The system seeks to add books, retrieve, and update book information for a large number of volumes. The functionality for user roles and student records will not be made in this project.

# Library Management System in C++ Key Factors.
Additionally, this project for a library management system has several OOP and POP capabilities.
The language of the source code is C++. To develop this project, we employed class and object ideas.

The ability of this library management system to store all information about books and their respective authors is its primary feature. In this system, we have provided five possibilities, which we shall now examine. We just used C++ for our programming.

# Features of the Project for a Library Management System
Students’ Information: We will have the ability to add or modify student information such as name, roll number, etc. These specifics will be kept in various variables.
Add/Remove/Update Books: This library management system will make adding, removing, and updating books easy.
Complete Book Details: This C++ software has all of the complete book details that are currently available in the shop.
Authentication: Using various roles, you can quickly sign in to the LMS service. If you’re an admin, you’ll be given a universal admin ID and password to access admin services.
Database: The database will be updated with any information that is added or removed. You can access and modify the database if you are an admin.


# Program Explanation
We first build the class “books” before declaring all of its internal functions and variables.
Then we define the book’s role and ask for its name, author, publisher, price, and stock.
Then we declare function body to show book id, book name, author, publisher, price, and stock on screen.
Switch case 3 searches for book’s char bname[20] and author’s aname[20].
Then, we compare the book and author names using strcmp().
We print Book Present if the comparison is successful; else cout and choice cin, we print Not Present.
We are utilizing a do-while loop for user selection.
So Program Explanation should be thoroughly read before checking the source code.


# Functions of Library Management System
When a department buys a new book, its entry is entered into the books database. Three alternatives are available.
Book: This option adds freshly bought books to the database. Author, title, publisher, price, and other form fields are input. The data must be accurate and entered in the right format.
This option is used to enter a new teacher’s data. This is the option for college-bound teachers.
This adds a student to the database. College students choose this choice.
DELETE clears database records. It’s used when someone quits college or a library book is discarded. This action requires approval from the library’s head since the system might lose crucial data.
It works on all databases with these three options:
Book: Enters a null value for the book whose accession number is entered. When a book is discarded, this is done.
Entering a teacher’s ID number clears their record. When a teacher graduates, they choose this.
Entering the student’s roll number deletes her record. This is decided by graduates.
UPDATE changes records. All three entries support this procedure.
This function isn’t needed to update a book’s status because the data doesn’t change.
Entering a teacher’s ID number updates her address, phone number, etc.
Student: Entering student’s roll number updates address, course, etc.
