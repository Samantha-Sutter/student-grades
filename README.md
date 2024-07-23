# Student Grades Application
## About
This C# console application manages student grades by reading data from a file and calculating the average grade and corresponding letter grade for each student. The application demonstrates core programming principles including file I/O, object-oriented design, and basic data manipulation.

## Technologies Used
- C#

## Features
- File Reading: Reads student data from a grades.txt file.
- Data Processing: Calculates average grades and assigns letter grades based on predefined criteria.
- Student Information Display: Outputs student IDs, names, average grades, and letter grades in a tabular format.
- Error Handling: Provides feedback if the file cannot be read or parsed.

## Components
- Student Class: Represents a student with properties for first name, last name, ID, and lists of earned and possible grades. Includes methods for grade calculation and letter grade assignment.
- StudentS Class: Manages a list of Student objects, handles file reading, and provides methods to retrieve student information.
- GradesUI Class: Handles the user interface, including reading data, displaying results, and error messages.
- Program Class: Entry point of the application, initializes UI and displays application information.

## How it Works
- Initialization: The Program class starts by displaying introductory information.
- File Reading: GradesUI invokes StudentS to populate student data from grades.txt.
- Data Processing: The StudentS class processes the file, calculates averages, and assigns letter grades.
- Display: The GradesUI class formats and outputs the student information to the console.

## Error Handling
- If there's an issue reading the file or parsing the data, an error message is displayed.

## Requirments
- .NET Core or .NET Framework
- A grades.txt file with student data formatted as specified in the comments of the StudentS class.
