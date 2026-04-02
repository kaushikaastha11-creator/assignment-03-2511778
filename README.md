# assignment-03-2511778

# Python Programming Assignments — Parts 1 to 4

**Language:** Python 3
**Environment:** Jupyter Notebook / Google Colab

---

## Overview

This repository contains 4 Python assignments covering core programming
concepts from basics all the way to machine learning. Each part builds
on the previous one, progressively introducing new concepts and tools.

---

## Repository Structure

part1_grade_tracker.ipynb       # Part 1 — Python Basics & Control Flow
part2_order_system.ipynb        # Part 2 — Data Structures
part3_api_files.ipynb           # Part 3 — File I/O, APIs & Exception Handling
part4_visualization_ml.ipynb    # Part 4 — Data Visualization & Machine Learning
students.csv                    # Dataset used in Part 4
python_notes.txt                # Generated file from Part 3
error_log.txt                   # Generated error log from Part 3
plot1_bar.png                   # Part 4 plots
plot2_histogram.png
plot3_scatter.png
plot4_box.png
plot5_line.png
plot6_seaborn_bar.png
plot7_seaborn_scatter.png
plot8_feature_importance.png

---

## Part 1 — Python Basics & Control Flow
**Theme:** Student Grade Tracker

### What I built:
A command-line Student Grade Tracker that manages student data,
computes results, and provides a summary report.

### Tasks:
- Task 1: Clean and parse raw student data (whitespace, casing, type conversion)
- Task 2: Analyse marks using for/while loops and conditionals
- Task 3: Generate a class performance summary report
- Task 4: String manipulation operations on a student essay

### Concepts Learned:
- String methods: .strip(), .title(), .split(), .upper(), .lower()
- Type conversion, f-strings, for/while loops
- try/except for input validation
- sum(), max(), min(), round()

---

## Part 2 — Data Structures
**Theme:** Restaurant Menu & Order Management System

### What I built:
A Restaurant Order Management System using nested lists,
dictionaries, and functions to manage a menu, cart, inventory,
and daily sales log.

### Tasks:
- Task 1: Explore and display the menu grouped by category
- Task 2: Simulate cart operations (add, update, remove, order summary)
- Task 3: Track inventory with deep copy protection
- Task 4: Analyse daily sales log data


---

## Part 3 — File I/O, APIs & Exception Handling
**Theme:** Product Explorer & Error-Resilient Logger

### What I built:
A program that fetches real product data from a public API,
processes it, saves results to files, and handles all failure
scenarios gracefully.

### Tasks:
- Task 1: Read and write files, keyword search
- Task 2: Fetch products from DummyJSON API (GET and POST requests)
- Task 3: Exception handling (ZeroDivisionError, FileNotFoundError, ConnectionError)
- Task 4: Timestamped error logger that writes to error_log.txt


---

## Part 4 — Data Visualization & Machine Learning
**Theme:** Student Performance Analysis & Prediction

### What I built:
A complete data analysis and machine learning pipeline that analyses
student performance, produces 7 visualizations, and predicts whether
a student will pass or fail.

### Tasks:
- Task 1: Data exploration with pandas (shape, dtypes, describe, grouping)
- Task 2: 5 Matplotlib plots (bar, histogram, scatter, box, line)
- Task 3: 2 Seaborn plots (bar chart, regression scatter plot)
- Task 4: Logistic Regression model with feature importance and bonus prediction

### Concepts Learned:
- pandas: DataFrames, .head(), .describe(), .mean(), .value_counts()
- matplotlib: bar, histogram, scatter, box, line charts
- seaborn: barplot, regplot
- scikit-learn: train_test_split, StandardScaler, LogisticRegression
- Feature importance via model coefficients

---

## How to Run

1. Clone this repository
2. Open any notebook in Jupyter Notebook or Google Colab
3. Run all cells in order from top to bottom

---

## Libraries Used

| Library      | Used In        | Purpose                        |
|--------------|----------------|--------------------------------|
| pandas       | Part 4         | Data loading and exploration   |
| matplotlib   | Part 4         | Data visualization             |
| seaborn      | Part 4         | Advanced visualization         |
| scikit-learn | Part 4         | Machine learning               |
| requests     | Part 3         | API calls                      |
| datetime     | Part 3         | Timestamping error logs        |
| copy         | Part 2         | Deep copying dictionaries      |
| numpy        | Part 4         | Numerical operations           |
