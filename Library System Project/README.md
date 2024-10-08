# Library Management System

A Python-based CLI application designed to streamline library operations. It utilizes OOP principles to manage books, users, and borrowing activities efficiently.

## Structure Overview

### User
The `User` class represents a library user and includes the following attributes:
- `id`: Unique identifier for the user.
- `name`: Name of the user.

### Book
The `Book` class represents a book in the library and includes the following attributes:

- `id`: Unique identifier for the book.
- `name`: Title of the book.
- `quantity`: Number of copies available.

### Admin
The `Admin` class manages the library system and provides various functionalities, including:

- Adding new books to the library.
- Printing all available books.
- Searching for books by name.
- Adding new users to the system.
- Borrowing books.
- Returning books.
- Printing users who borrowed books.
- Printing all users in the system.

## Features

- **Add Books**: Add new books with unique IDs.
- **Manage Users**: Add new users to the system.
- **Search Books**: Search for books by name using a prefix.
- **Borrow and Return**: Borrow books from the library and return them when done.
- **Track Borrowers**: Keep track of users who have borrowed books.
- **User Interface**: Simple CLI.


**Example Usage:**

```
Program Options:
 1) Add book
 2) Print library books
 3) Print books by prefix
 4) Add user
 5) Borrow book
 6) Return book
 7) Print users borrowed book
 8) Print users

Enter your choice from 1 to 8: 1

Please Enter the book id: 100
Please Enter the book name: The Lord of the Rings
Please Enter the book quantity: 3

Book is added successfully!

(Continue using the menu to manage your library...)
```
