# ASCII Art Generator Using Pure Python

A lightweight ASCII Art Generator built using only core Python concepts.
No external libraries, no dependencies, just logic, loops, and condition based design.

This project demonstrates how structured visual output can be created inside a terminal by treating it as a two dimensional grid and controlling each character position through code.

Features
	•	Pure Python implementation
	•	No third-party libraries required
	•	Fully customizable output
	•	Uses only loops and conditional statements
	•	Works in any terminal where Python is installed

How It Works

The terminal is treated like a grid made of rows and columns.
	•	Each row represents vertical movement
	•	Each column represents horizontal movement

Nested loops iterate through this grid.
At every position, conditions decide which character should be printed.

If a condition matches, a symbol like @, #, % is printed.
If not, a blank space is printed.

Many small logical decisions together form a complete ASCII image.

# Example Logic

for row in range(height):
    for col in range(width):
        if row == 5 and 10 <= col <= 15:
            print("@", end="")
        else:
            print(" ", end="")
    print()

    This simple logic scales to complex designs when expanded across multiple rows and conditions.


    Why This Project

Most ASCII art generators rely on libraries that hide the logic.

This project focuses on:
	•	understanding how output is structured
	•	improving logical and spatial thinking
	•	gaining full control over visual layout

It is ideal for learners who want to strengthen fundamentals instead of relying on abstractions.


Use Cases
	•	Terminal based applications
	•	Learning programming fundamentals
	•	Visual debugging output
	•	Educational demonstrations
	•	Retro or minimal text based projects


Getting Started
	1.	Install Python (3.x recommended)
	2.	Clone this repository
	3.	Run the Python file in your terminal
	4.	Modify conditions to create your own designs


Customization

You can customize:
	•	canvas size (rows and columns)
	•	characters used
	•	complexity of patterns
	•	spacing and density

Every change directly affects the visual output.


Requirements
	•	Python 3.x
No additional packages required.
