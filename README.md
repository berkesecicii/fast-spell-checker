# Fast Spell Checker (C)

A high-performance spell checker built in **C** that loads a dictionary of words into memory and checks text files for misspellings at scale. This project was developed to demonstrate low-level memory management and the implementation of custom data structures.

### 🚀 Key Features
*   **Custom Hash Table:** Implements a custom hash function and a hash table data structure to store and retrieve tens of thousands of words with near O(1) time complexity.
*   **Memory Management:** Strictly manages memory allocation and deallocation using `malloc`, `calloc`, and `free` to prevent memory leaks (verified via Valgrind).
*   **File I/O:** Efficiently reads and processes large text files and dictionary databases byte-by-byte.
*   **Low-Level Optimization:** Utilizes pointers, linked lists, and optimized string hashing for maximum processing speed.

### 💻 Technology Stack
*   **Language:** C
*   **Concepts:** Data Structures (Hash Tables, Linked Lists), Memory Management, Pointers
*   **Tools:** GCC, Make, Valgrind
