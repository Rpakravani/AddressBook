📘 **Address Book Manager** (C)
A command‑line address book application written in C that demonstrates dynamic memory management, file I/O, string handling, and modular program design.
This project was built to practice low‑level systems programming concepts while implementing a fully functional contact management tool.

🚀 **Features**
- Add new contacts
- Insert contacts in alphabetical order
- Remove contacts by index or full name
- Edit existing contacts
- List all contacts
- Save contacts to file (input format)
- Export human‑readable reports
- Load, append, or merge contacts from files
- Duplicate detection
- Robust input validation

🧠 **Technical Highlights**
  Dynamic Memory Management
- Contacts are stored in a NULL‑terminated dynamic array using malloc, realloc, and free.
  File Parsing
- Supports loading, appending, and merging contacts from structured text files.
  String Handling
- Uses strdup, fgets, and manual newline stripping for safe input handling.
  Input Validation
- Phone numbers, names, and ages are validated with retry logic.
  Modular Design
- All major operations are implemented as separate functions for clarity and maintainability.

📂 **File Structure**

/address-book
│── addressbook.c       Main program and all functionality

│── README.md           Project documentation

│── sample_input.txt    Example input file

│── output_report.txt   Example human-readable output

🖥️ **How to Compile & Run**
- gcc addressbook.c -o addressbook
- ./addressbook

📄 **Example Input File Format**

John
Doe
123 Main St
6041234567
25

🔧 **Future Improvements**
- Convert to linked list for more efficient insert/remove
- Add search functionality
- Add JSON or CSV import/export
- Add unit tests
- Add a GUI or web interface





