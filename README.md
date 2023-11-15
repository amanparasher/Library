# E-Library Management System

This simple C program implements a basic E-Library Management System, allowing users to add book information, display book information, list books by a specific author, and obtain the count of books in the library.

## Features
- Add book information: Enter details such as book name, author name, number of pages, and price.
- Display book information: View the details of all entered books.
- List books by author: Retrieve and display books by a specified author.
- Count of books: Obtain the total count of books in the library.
- Exit: Terminate the program.

## How to Use
1. Compile the program using a C compiler.
    ```bash
    gcc e_library.c -o e_library
    ```

2. Run the compiled executable.
    ```bash
    ./e_library
    ```

3. Follow the on-screen menu to perform the desired actions.

## Usage Instructions
- When adding book information (Option 1), enter the book name, author name, pages, and price as prompted.
- To display book information (Option 2), all entered books' details will be shown.
- When listing books by author (Option 3), enter the author's name to view the corresponding books.
- To check the total count of books in the library (Option 4), select the respective option.

## Sample Usage
```plaintext
WELCOME TO E-LIBRARY

1. Add book information
2. Display book information
3. List all books of given author
4. List the count of books in the library
5. Exit

Enter one of the above: 1
Enter book name = Programming101
Enter author name = JohnDoe
Enter pages = 300
Enter price = 25.50

WELCOME TO E-LIBRARY

1. Add book information
2. Display book information
3. List all books of given author
4. List the count of books in the library
5. Exit

Enter one of the above: 2
you have entered the following information
book name = Programming101   author name = JohnDoe   pages = 300   price = 25.500000

WELCOME TO E-LIBRARY

1. Add book information
2. Display book information
3. List all books of given author
4. List the count of books in the library
5. Exit

Enter one of the above: 3
Enter author name : JohnDoe
Programming101 JohnDoe 300 25.500000

WELCOME TO E-LIBRARY

1. Add book information
2. Display book information
3. List all books of given author
4. List the count of books in the library
5. Exit

Enter one of the above: 4
No of books in library: 1

WELCOME TO E-LIBRARY

1. Add book information
2. Display book information
3. List all books of given author
4. List the count of books in the library
5. Exit

Enter one of the above: 5
```

Feel free to use and modify this simple E-Library Management System according to your needs.
