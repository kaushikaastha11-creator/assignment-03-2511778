# Assignment — Part 4: Data Visualization & Machine Learning

**Theme:** Student Performance Analysis & Prediction

---

## Overview

A complete data analysis and machine learning pipeline that analyses
student performance data, produces meaningful visualizations, and builds
a classifier to predict whether a student will pass or fail.

---

## Dataset

students.csv — 15 students with the following columns:
- name, math, science, english, history, pe
- attendance_pct, study_hours_per_day, passed (1=Pass, 0=Fail)

---

## Tasks

### Task 1 — Data Exploration with Pandas (5 marks)
- Load dataset and print first 5 rows
- Print shape and data types of each column
- Print summary statistics (mean, min, max, std)
- Print count of students who passed and failed
- Compute average score per subject for passing vs failing students
- Find and print the student with the highest overall average

### Task 2 — Data Visualization with Matplotlib (8 marks)

5 plots produced and saved as .png files:

- plot1_bar.png     — Average score per subject (bar chart)
- plot2_histogram.png — Distribution of math scores with mean line
- plot3_scatter.png — Study hours vs average score (Pass=green, Fail=red)
- plot4_box.png     — Attendance distribution for Pass vs Fail
- plot5_line.png    — Math and science scores per student (line plot)

### Task 3 — Data Visualization with Seaborn (4 marks)

2 plots produced and saved as .png files:

- plot6_seaborn_bar.png     — Average math and science score by Pass/Fail
- plot7_seaborn_scatter.png — Attendance vs average score with regression lines

Seaborn vs Matplotlib comparison:
Seaborn required less code to produce polished plots compared to Matplotlib.
regplot() automatically added regression lines without extra steps.
Matplotlib gave more manual control but required more lines of code for styling.

### Task 4 — Machine Learning with scikit-learn (8 marks + 2 bonus)

Features used: math, science, english, history, pe, attendance_pct, study_hours_per_day
Target: passed (1=Pass, 0=Fail)

- Step 1: Split data into 80% train and 20% test, scale using StandardScaler
- Step 2: Train a LogisticRegression model, print training accuracy
- Step 3: Predict on test set, print accuracy and correct/wrong predictions
- Step 4: Extract and plot feature coefficients (green=Pass, red=Fail)
- Step 5 (Bonus): Predict pass/fail for a new student with probability score


---

## File Structure

part4_visualization_ml.ipynb    # Main notebook with all 4 tasks
students.csv                    # Dataset with 15 student records
plot1_bar.png                   # Average score per subject
plot2_histogram.png             # Math score distribution
plot3_scatter.png               # Study hours vs average score
plot4_box.png                   # Attendance distribution
plot5_line.png                  # Math and science per student
plot6_seaborn_bar.png           # Seaborn bar chart
plot7_seaborn_scatter.png       # Seaborn regression scatter
plot8_feature_importance.png    # ML feature coefficients

---

## Libraries Used

- pandas       — data loading and exploration
- matplotlib   — data visualization (5 plots)
- seaborn      — advanced visualization (2 plots)
- scikit-learn — machine learning (train/test split, scaling, logistic regression)
- numpy        — numerical operations
