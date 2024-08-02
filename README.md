# Library Management System
The Library Management System is designed to manage library operations efficiently. It allows users to register, log in, and access various functionalities to manage members, authors, and books. This system ensures smooth library management through a user-friendly interface and robust backend.

 ## Key Features:
-> User Registration and Login:

Users can create an account by providing necessary details.
Secure login functionality ensures that only registered users can access the system.
-> Member Management:

Add, edit, and delete member information.
View a list of all members with detailed profiles.
Search for members using various criteria.
-> Author Management:

Add new authors to the system.
Edit and update author details.
Remove authors and view a comprehensive list of all authors.
-> Book Management:

Add new books to the library collection.
Edit book details, including title, author, and genre.
Delete books and maintain an updated inventory.
Search for books using filters such as title, author, and genre.
## Tech Stack:
 * Backend:

C++: Core language for implementing the system logic.
Qt: Framework for building the user interface and managing backend logic.
qmake: Build system tool for managing the project build process.
 * Database:

SQLite: Lightweight database for storing user, member, author, and book information.
Frontend:

Qt Widgets: For creating the graphical user interface.
QML (optional): For a more modern and dynamic user interface.
## Project Implementation:
-> Registration and Login:

Implemented using secure hashing for passwords.
User authentication to ensure data protection and access control.
-> Member Management:

Interface to add, edit, view, and delete members.
Search functionality to find specific members quickly.
-> Author Management:

Features to add, update, and remove authors.
Comprehensive list view for easy management.
-> Book Management:

Capabilities to add, edit, and delete books.
Search and filter options for efficient book retrieval.
## Why This Project Matters:
The Library Management System simplifies and automates library operations, making it easier for librarians and staff to manage books, members, and authors. By providing a secure and efficient way to handle library data, this system enhances the overall library experience for both staff and users.


## Project Structure
_____________________________________________________________________________________________________
```
QT_Library_Manag/
│
├── .gitignore
├── lib.iml
├── modules.xml
├── base.xml
├── color.xml
├── icons.qrc
│
├── addbook.cpp
├── addmember.cpp
├── authorslist.cpp
├── booklist.cpp
├── deletebook.cpp
├── deletemember.cpp
├── digitallibrary.cpp
├── editbook.cpp
├── editmember.cpp
├── genrelist.cpp
├── issuebook.cpp
├── login.cpp
├── main.cpp
├── manageauthors.cpp
├── managebooks.cpp
├── memberslist.cpp
├── newpasswd.cpp
├── returnbook.cpp
├── signup.cpp
│
├── Database.h
├── addbook.h
├── addmember.h
├── authorslist.h
├── booklist.h
├── deletebook.h
├── deletemember.h
├── digitallibrary.h
├── editbook.h
├── editmember.h
├── genrelist.h
├── issuebook.h
├── login.h
├── manageauthors.h
├── managebooks.h
├── memberslist.h
├── newpasswd.h
├── returnbook.h
├── signup.h
│
├── addbook.ui
├── addmember.ui
├── authorslist.ui
├── booklist.ui
├── deletebook.ui
├── deletemember.ui
├── digitallibrary.ui
├── editbook.ui
├── editmember.ui
├── genrelist.ui
├── issuebook.ui
├── login.ui
├── manageauthors.ui
├── managebooks.ui
├── memberslist.ui
├── newpasswd.ui
├── returnbook.ui
├── signup.ui
│
├── book.png
├── book1.png
├── book2.png
├── book3.png
├── froggy.png
├── login-book.png
├── logo.png
│
├── qt.jpg
│
├── loadingBook.gif
│
├── Library.pro
├── Library.pro.user
├── Library.pro.user.11e0e32
├── Library.pro.user.353414c
├── Library.pro.user.5d31b3b
├── Library.pro.user.79cbd9a
├── Library.pro.user.fe6540e
```
