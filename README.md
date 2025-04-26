📚 Library Management System
This is a simple Console-Based Library Management System developed in Python.
It allows users to efficiently manage a collection of books with multiple features like viewing, adding, issuing, and returning books.

✨ Features
View Books List
Display all available books with their ID, Name, Author, and current Status (Available/Issued).

Add a Book
Add a new book by providing its ID, Name, and Author. Each newly added book is automatically marked as "Available".

Remove a Book
Delete any book from the library collection using its unique Book ID.

Search for a Book
Search for books by their name (case-insensitive search) and view matching results.

Issue a Book
Issue a book by its ID. If the book is available, its status is updated to "Issued".

Return a Book
Return a previously issued book by updating its status back to "Available".

Exit the System
Option to gracefully exit the program.

📋 How It Works
The system uses a dictionary to store book details.

Book IDs are prefixed with bk (example: bk1, bk2, etc.).

Book status is automatically managed based on issuing or returning actions.

Clear and simple text-based interface with prompts for user input.

🚀 Getting Started
To run the program:

Make sure Python is installed.

Copy the code into a .py file.

Run the file using any Python IDE or the command line:

📌 Notes
Ensure you enter numeric IDs (only numbers) when adding, removing, issuing, or returning books.

Book searches are case-insensitive, meaning "Harry Potter" and "harry potter" will be treated the same.


--------------------------------------------------
                    Welcome to Our Library Management System
--------------------------------------------------
Enter any one option from the following given option/s
 1: View Books List 
 2: Add Book 
 3: Remove Book 
 4: Search Book 
 5: Issue Book 
 6: Return Book 
 7: Exit
