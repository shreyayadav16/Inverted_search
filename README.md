# Inverted_search
The Inverted Search System is a console-based application written in C that creates an index of words from multiple text files. It allows users to search for any word and find the files in which that word appears along with the number of occurrences.
The system uses a Hash Table based Inverted Index to efficiently store and retrieve word information.
# Features
- Validate and process multiple input files
- Build an inverted index database
- Display complete database contents
- Search for a specific word across files
- Save database to a backup file
- Load database from backup
- Menu-driven user interface

# Technologies used
- C programming
- Data structure(Linked List)
- Hash table
- File handling
- Dynamic memory allocation

# Compilation
compile the project using GCC:
  gcc main.c database.c helper.c validate.c -o inverted search

# Execution
Run the program by passing input text files: 
  ./inverted_search file1.txt file2.txt
  
 
