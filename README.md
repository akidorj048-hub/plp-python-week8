PLP Python Week 8 — Toolkit Plan

Project Overview

My Python Toolkit is a menu-driven command-line program created for the PLP Python Week 8 assignment. It provides three tools: a simple calculator, a to-do list, and a number checker. The user can select a tool, use it, and return to the main menu until they choose to quit.

Tools Included

Simple Calculator: Performs addition, subtraction, multiplication, and division.

To-Do List: Allows users to add, view, and remove tasks.

Number Checker: Identifies whether a whole number is positive, negative, or zero, and whether it is even or odd.

Python Concepts Practised

Variables and data types

User input and output

Type conversion using int() and float()

Conditional statements: if, elif, and else

Loops: while and for

Lists and list methods such as append() and pop()

Functions and reusable code

F-strings

Error handling using try and except

Comments and readable program structure

Project Files

toolkit_plan.txt — the plan for the toolkit.

toolkit.py — the complete Python program.

screenshots/ — screenshots showing the menu, invalid choice, and each tool in action.

How to Run

Install Python 3 if it is not already installed.

Download or clone this repository.

Open a terminal in the project folder.

Run:

python toolkit.py

On Windows, you can also try py toolkit.py.

Choose an option from the menu and follow the instructions.

Reflection
## Reflection

The most challenging part of this project was designing the menu loop so that users could select different tools and return to the main menu without restarting the program. The bug that took me the longest to fix was handling invalid user input, especially when someone entered letters instead of numbers or selected a task number that did not exist. I fixed these issues by using `try` and `except` blocks to handle invalid numeric input and conditional statements to validate menu choices and task numbers. I also learned how to use Python lists with `append()` and `pop()` to add and remove tasks safely. This project helped me understand how loops, functions, conditionals, and user input work together to create an interactive program. I improved my coding skills by organizing the tools into separate functions and adding comments and friendly messages to make the code easier to understand. If I had one more week, I would add file storage so that tasks could be saved and loaded even after the program closes, as well as a feature that allows users to mark completed tasks.
  
