A console-based Library Management System developed in C++ to efficiently manage books, borrowing records, and administrative tasks for a university or public library.  
This project focuses on **file handling, data structuring, and menu-driven programming** to provide a fully functional and secure library management experience.

--
**Features**

### **Admin Authentication**
- Secure login with **username** and **password**.
- Session expires on logout for security.

### **Book Management**
- **View All Books**: Displays index, book name, ISBN, and author.
- **Add Books**: Add new books to the library’s collection.
- **Delete Books**: Remove a book using its ISBN.
- **Search Book**: Search by ISBN and display full details with availability status.

### **Borrowing & Lending**
- **Lent Books List**: Displays all borrowed books with:
  - Book details (index, name, ISBN, author)
  - Borrower details (name, roll number, phone, department)
  - Date of issuance & return date
- **Return Book**: Deletes borrower’s record upon return.

### **Account Management**
- Change username and password (with validation of current password before update).

---

## Technologies Used
- **Language:** C++
- **Concepts:** File handling, arrays/structs, menu-driven programming, loops & conditions.
- **Data Storage:** Text file-based persistence.

---

## Project Structure
- LibraryManagement.cpp
- books.txt
- borrowed_books.txt
- readme.md
