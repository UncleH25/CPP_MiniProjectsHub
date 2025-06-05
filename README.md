# 📚 C++ Mini Projects Hub
Welcome to the central repository for my small C++ projects!

Each project was created to practise and reinforce a specific concept in C++ programming. This hub provides an easy way to navigate through them, understand their purpose, and see what was learnt in each.

These mini-projects are designed to build confidence and fluency in writing, compiling, and running simple C++ programs.

## 🔤 Basics of a C++ Program 
The following programs focus on the following core aspects:
* Understanding the structure of a basic C++ program
* Using `#include <iostream>` and the `std` namespace
* Basic declaring and initialising of varibles (`string`,`int`,`char`)
* Working with `const` values for fixed data
* Accpeting user input with `cin` and displaying output with `cout`
* Performing basic arithmetic operations (excluding the modulo operator)
* Writing clean, well-commented code


### Project 1
[**Simple USD/ZAR Currency Converter**](https://github.com/UncleH25/Simple-USD-ZAR-Currency-Converter)

*A basic C++ program that converts US Dollars (USD) to South African Rands (ZAR) using a fixed exchange rate.*

*Allows users to input an amount in USD and calculates the equivalent amount in ZAR based on a predefined exchange rate.*
### Project 2
[**BMI Calculator**](https://github.com/UncleH25/BMI-Calculator)

*A basic C++ program that calculates your Body Mass Index (BMI) using your height (in centimetres) and weight (in kilograms).*

*Takes in the user's height and weight, converts the height from centimetres to metres, and calculates their BMI*
### Project 3
[**Reciept Generator**](https://github.com/UncleH25/Receipt-Generator)

*A simple C++ console application that generates a receipt for three products, calculating totals and including VAT.*

*Prompts the user to enter the names, prices, and quantities of three products, calculates the total cost, adds 15.5% VAT, and prints a formatted receipt.*

## 🧾 Input and Output in C++
The following programs focus on the following input/output concepts:
* Using `cin` to read input from the user
* Using `cout` to display output to the screen
* Reading multiple inputs in a single line using the extraction operator `>>`
* Skipping whitespace automatically with `cin` and understanding how it handles different data types
* Reading characters (including spaces) using `cin.get()`
* Handling input errors using `cin.clear()` and `cin.ignore()`
* Formatting output with manipulators such as `setprecision`, `fixed`, `showpoint`, and `setw`
* Reading full lines of text using `getline()`
* Using `cout` to debug logic errors during development


## Project 4
[**Parking Fee Calculator**](https://github.com/UncleH25/Library-Checkout-System)

*A simple C++ console application that calculates the total parking fee based on the entry and exit times. It displays a neatly formatted receipt showing the total time parked and the amount due.*

*Prompts the user to enter the entry and exit times in hours and minutes. It then calculates the total parking time, breaks it into full hours and remaining minutes, and applies the hourly and per-minute rates to generate the final fee.*

## Project 5
[**Library Checkout System**](https://github.com/UncleH25/Library-Checkout-System)

*A C++ console program that calculates and displays a checkout fee summary based on how long a book is borrowed and whether it is a textbook or not. The program collects user details and book information, then outputs a neatly formatted receipt.*

*Prompts the user for their name, the book title, the number of days the book is due in, and whether the book is a textbook. It then calculates two possible fees: one for a normal book and one for a textbook—both based on fixed daily rates.*

**Note: The program calculates both fees regardless of the actual book type. The user must refer to the correct one based on the Y/N input.**

## Project 6
[**Power And Character Converter**](https://github.com/UncleH25/Power-And-Character-Converter)

*A C++ console application that performs two separate functions:*

*1. Calculates the result of raising a base to an exponent using the `pow()` function.*

*2. Accepts a character input and displays its ASCII value, as well as the previous and next characters.*

*Power Calculator: Prompts the user for a base and an exponent, then computes the result using the `pow()` function from the `<cmath>` library.*

*Character Analysis: Takes a single character as input and displays its ASCII value, the character that comes before it, and the one that comes after it.*

## Project 7
[**Expense Tracker With File I/O**](https://github.com/UncleH25/Expense-Tracker)

*A C++ program that reads expense data from a file (`expenses.txt`), calculates VAT and total amounts for each entry, and generates a neatly formatted receipt saved to an output file (`receipt.txt`).*

*It reads expense categories and amounts from a file, calculates a 15% VAT for each item, adds it to the amount, and writes a detailed receipt to a separate file. It also calculates the overall total including VAT.*

*The receipt is formatted into columns using I/O manipulators to ensure clean and readable output.*

## 🔀 Introduction to Control Structures (Selection)

The following programs focus on learning how to make decisions in a program using conditional logic:
* Using `if` statements for one-way selection (run only if a condition is true)
* Using `if...else` statements for two-way selection (choose between two paths)
* Comparing values using relational operators like `==`, `!=`, `<`, `>`, `<=`, and `>=`
* Working with logical operators `&&`, `||`, and `!` to combine conditions
* Using `char`, `int`, `double`, and `string` values in comparisons
* Nesting `if` statements to handle multiple alternatives
* Applying `bool` variables and expressions that evaluate to `true` or `false`
* Using input stream validation with `if (!inData)` to check if a file opened correctly
* Writing compound statements using `{}` to group multiple actions under a single condition
* Formatting output conditionally to enhance readability

## Project 8
[**Fever & Age Health Checker**](https://github.com/UncleH25/Health-Check-Analyser)

*A simple C++ console program that checks if a user is a minor or an adult, and whether they have a fever based on their temperature.* 

*It outputs an appropriate message based on both conditions and handles invalid input safely.*

## Project 9
[**Student Grading System**](https://github.com/UncleH25/Student-Grading-System)

*A simple C++ program that determines a student’s letter grade based on a given percentage score and displays it using a `switch` statement. The program also validates input using an assertion.*

## Project 10
[**Food Order Billing System**](https://github.com/UncleH25/Food-Order-Billing-System)

*A C++ program that simulates a basic food ordering and billing system. It allows users to select an item from a fixed menu, input the desired quantity, calculates the total cost, and applies a discount if applicable.*

## Project 11
[**Age Validator**](https://github.com/UncleH25/Age-Validator)

*A C++ program that reads a user's name and age from an input file (`input.txt`), determines their access level based on age, and writes the result to an output file (`access.txt`).*

## 🔁 Repetition Structures in C++

The following programs focus on repetition (looping) structures, which allow certain actions to be performed multiple times based on conditions.
* Using `while` loops for repeating actions while a condition remains true
* Designing counter-controlled, sentinel-controlled, flag-controlled, and EOF-controlled `while` loops
* Understanding how to initialize, test, and update loop control variables
* Using `for` loops when the number of repetitions is known in advance
* Using `do...while` loops for actions that must run at least once (common in input validation)
* Choosing the correct loop type based on the situation
* Controlling loop flow using `break` (to exit early) and `continue` (to skip to the next iteration)
* Using nested loops for repeated actions within repeated actions
* Debugging loops using tools like variable tracing and loop invariants
* Avoiding infinite loops by properly updating conditions and loop variables

## Project 12
[**ATM Withdrawal Simulator**](https://github.com/UncleH25/ATM-Withdrawal-Simulator)

*A C++ console program that simulates a simple ATM withdrawal system. Users can repeatedly withdraw money from their account until they choose to exit, while the program applies transaction fees and validates balance limits.*

## Project 13
[**Sales Performance Tracker**](https://github.com/UncleH25/Sales-Performance-Tracker)

*A C++ program that reads sales data from an input file, evaluates performance based on the amount sold, and writes a neatly formatted report with a status label to an output file.*

## Project 14
[**Calender Day Counter**](https://github.com/UncleH25/Calendar-Day-Counter)

*A C++ program that determines the number of days in a given month and year. It supports leap year detection for February and allows users to repeat the process for multiple inputs.*
