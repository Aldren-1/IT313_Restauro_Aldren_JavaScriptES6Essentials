# IT313 JavaScript ES6+ Essentials

## Enrollment Eligibility Checker

This project is a simple Node.js program that checks the grades of students and determines if they are **PASSING** or **PROBATION**.

A student passes if their average grade is **75 or higher**.

## How It Works

The program:

const for storing values that do not need to be reassigned
Arrow functions for creating functions
Destructuring to get values from student objects
Template literals for displaying the report
map() to calculate the average and status of each student
filter() to get the students who are passing
reduce() to calculate the class average
ES Modules to separate the grade functions into gradeUtils.js
Promises and setTimeout() to simulate retrieving enrollee data
async/await to wait for the enrollee data
try/catch to handle possible errors

It uses ES6+ features such as **arrow functions, destructuring, map(), filter(), reduce(), template literals, ES modules, Promises, async/await, and try/catch**.

## Files

* `main.js` – Main program and report generation.
* `gradeUtils.js` – Contains the grade calculation and passing-check functions.
* `package.json` – Project configuration for ES Modules.

## How to Run

Make sure Node.js is installed, then open the project folder in the terminal and run:

```bash
node main.js
```

The student results and class summary will be displayed in the terminal.

## Expected Result

```text
=== IT313 eligibility report ===
Ana Cruz - Average: 87.67 - PASSING
Bea Santos - Average: 65.00 - PROBATION
Cid Ramos - Average: 94.67 - PASSING
Dex Alonzo - Average: 55.00 - PROBATION
Eli Tan - Average: 78.00 - PASSING

Class Average: 76.07
Passing: 3 / 5
```
