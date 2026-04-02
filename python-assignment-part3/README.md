# Assignment — Part 3: File I/O, APIs & Exception Handling

**Theme:** Product Explorer & Error-Resilient Logger

---

## Overview

A program that fetches real product data from a public API, processes it,
saves results to files, and handles all failure scenarios gracefully —
just like a production-grade application.

---

## Tasks

### Task 1 — File Read & Write Basics

**Part A — Write:**
- Write 5 student notes to python_notes.txt using write mode
- Append 2 additional lines using append mode
- Print confirmation message after each file operation

**Part B — Read:**
- Read the file back and print each line with a number
- Count and print total number of lines
- Ask user for a keyword and print all matching lines (case-insensitive)

### Task 2 — API Integration 

- Fetch 20 products from https://dummyjson.com/products and display in a formatted table
- Filter products with rating >= 4.5 and sort by price (high to low)
- Fetch all products in the laptops category
- Send a POST request to simulate creating a new product

### Task 3 — Exception Handling 

**Part A — Guarded Calculator:**
- safe_divide() function handles ZeroDivisionError and TypeError

**Part B — Guarded File Reader:**
- read_file_safe() function handles FileNotFoundError
- finally block always runs whether file is found or not

**Part C — Robust API Calls:**
- All API requests wrapped in try/except blocks
- Handles ConnectionError, Timeout, and unexpected errors

**Part D — Input Validation Loop:**
- Validates product ID input (must be integer between 1-100)
- Makes API call only with valid input
- Checks response status code for 200 and 404
- Continues until user types quit

### Task 4 — Logging to File

- log_error() function writes timestamped entries to error_log.txt
- Opens file in append mode so logs accumulate across runs
- Intentionally triggers two logged entries:
  - ConnectionError via unreachable URL
  - HTTP 404 error via invalid product ID
- Prints full contents of error_log.txt at the end


---

## Concepts Used

- File I/O: open(), read(), write(), append mode
- requests library: GET and POST requests
- JSON parsing with .json()
- try/except/finally for exception handling
- datetime module for timestamps
- Input validation with while loops
- HTTP status code checking
