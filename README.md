# Library Manager CLI

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![License](https://img.shields.io/badge/License-MIT-green)

A command-line application to manage your personal book library. This Python-based tool allows you to add, remove, search, and display books, as well as view statistics about your library. The program also includes file handling to save and load your library data automatically.

---

## Features

- **Add a Book**: Add a new book to your library with details like title, author, publication year, genre, and read status.
- **Remove a Book**: Remove a book from your library by its title.
- **Search for a Book**: Search for books by title or author.
- **Display All Books**: View all books in your library in a formatted list.
- **Display Statistics**: See the total number of books and the percentage of books you've read.
- **Save and Load Library**: Automatically save your library to a file (`library.txt`) when you exit the program and load it when you start the program again.

---

## Requirements

- Python 3.8 or higher
- No additional libraries or dependencies required

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/library-manager-cli.git
   ```
2. Navigate to the project directory:
   ```bash
   cd library-manager-cli
   ```

---

## Usage

1. Run the program:
   ```bash
   python library_manager.py
   ```
2. Follow the on-screen menu to manage your library:
   ```
   Welcome to your Personal Library Manager!
   1. Add a book
   2. Remove a book
   3. Search for a book
   4. Display all books
   5. Display statistics
   6. Exit
   Enter your choice:
   ```
3. Use the options to add, remove, search, or view books and statistics.
4. When you exit the program, your library data will be saved automatically to `library.txt`.

---

## File Handling

The program automatically saves your library data to a file named `library.txt` in the same directory as the script. When you restart the program, it loads the library data from this file.

- **First Run**: If `library.txt` does not exist, the program starts with an empty library.
- **Subsequent Runs**: The program loads the library data from `library.txt` if it exists.

---

## Example Workflow

### Add a Book
```
Enter the book title: The Great Gatsby
Enter the author: F. Scott Fitzgerald
Enter the publication year: 1925
Enter the genre: Fiction
Have you read this book? (yes/no): yes
Book added successfully!
```

### Display All Books
```
Your Library:
1. The Great Gatsby by F. Scott Fitzgerald (1925) - Fiction - Read
2. 1984 by George Orwell (1949) - Dystopian - Unread
```

### Display Statistics
```
Total books: 2
Percentage read: 50.0%
```

### Exit
```
Library saved to file. Goodbye!
```

---

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your branch to your forked repository.
5. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Inspired by the need for a simple, command-line-based library management tool.
- Built with Python for ease of use and accessibility.

---

## Contact

For questions or feedback, please reach out to [me via email](mailto:your.abdulrehmanbinadeem@gmail.com).

```

---

### How to Use This README.md:
1. Copy the content above into a file named `README.md`.
2. Replace placeholders like `your-username`, `Your Name`, and `your.email@example.com` with your actual GitHub username, name, and email.
3. Save the file in the root directory of your GitHub repository.

This `README.md` provides a clear and professional overview of your project, making it easy for users and contributors to understand and use your Library Manager CLI. Let me know if you need further assistance! 😊
