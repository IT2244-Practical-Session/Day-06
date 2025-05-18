# Day-06
# Bash Script Collection

This repository contains a collection of Bash scripts that demonstrate basic shell scripting concepts. Below is a summary of each script and its functionality.

## 1. Display Calendar and Date

This script displays the current month calendar and date information using the following commands:

* **cal**: Displays the calendar of the current month.
* **date +%d**: Displays the current day of the month.
* **date**: Displays the full date and time.

## 2. Student Marks Calculator

This script prompts the user to enter a student's name and marks for three subjects, then calculates and displays the total and average marks.

* Uses **read** to get input.
* Uses arithmetic operations for calculations.

## 3. Simple Calculator

This script performs basic arithmetic operations (addition, subtraction, division, multiplication) based on user input.

* Uses **read** to accept two numbers.
* Performs calculations using arithmetic expressions.

## 4. Day Finder

This script takes a number (1-7) as input and displays the corresponding weekday.

* Uses a **case** statement to map numbers to days.

## 5. Username Verification

This script verifies whether the entered username matches a predefined value.

* Uses an **if** statement to compare the input.

## 6. Number Comparison

This script takes two numbers as input and determines which one is greater and which is smaller.

* Uses **if-else** statements for comparison.

## 7. Calculator using 'expr' Command

This script performs arithmetic operations similar to the simple calculator but uses the **expr** command for calculations.

## Usage

To execute any script, follow these steps:

1. Grant execute permission:

   ```bash
   chmod 777 script_name.sh
   ```
2. Run the script:

   ```bash
   ./script_name.sh
   ```

## Author

Dinuka Avindra Silva
