Project 6: Student Grade Calculator

Overview
A C++ console application that takes 5 subject marks, calculates the total and average, and assigns a final letter grade. This project highlights the ability to return multiple values from a single `void` function using pass-by-reference.

Features
Array Processing: Iterates through an array of marks to calculate the total score.
Instant Fail Condition: Automatically assigns an "F" (Fail) if any single subject score falls below 35, overriding the overall average.
Boundary Logic: Uses exact relational operators (`>=`) to accurately assign grades (A, B, C) based on the calculated average.

Concepts Mastered
* Pass-by-Reference (`&`) for multiple outputs (`total`, `average`, `grade`).
* Array iteration and accumulation.
* Complex control flow and edge-case handling.
