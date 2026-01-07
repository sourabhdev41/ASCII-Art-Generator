# Image to ASCII Art Using Python

Project Purpose

This project demonstrates how an image-like structure can be represented using ASCII characters through pure Python logic .

Instead of relying on image processing libraries, the program manually constructs an ASCII output by mapping row and column positions to specific characters using nested loops and conditional statements .

The main focus of this project is to strengthen core programming concepts such as :
	•	Understanding nested loops
	•	Practicing if / elif conditional logic
	•	Learning pattern-based thinking
	•	Creating visual output in the console


How the Code Works

The ASCII image is treated as a two-dimensional grid with a fixed height and width .
	•	The program uses two nested for loops to iterate through each row and column
	•	For every (row, column) position, a character is selected using if and elif conditions
	•	Different ASCII characters like . : - = + * # % are used to represent different visual intensities
	•	print(char, end='') is used to print characters on the same line
	•	After finishing one row, a new line is printed to move to the next row

By repeating this logic for all rows and columns, a complete ASCII image is generated directly in the terminal .


How to Run the Program

Requirements
	•	Python 3.x installed on your system

Steps to Run
	1.	Clone or download this repository
	2.	Open a terminal in the project directory
	3.	Run the following command :

python ascii_art.py

The ASCII output will be displayed directly in the terminal .



This project is ideal for beginners who want to understand how simple logic can create structured visual output without using any external libraries .
