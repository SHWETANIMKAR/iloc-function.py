# Patient Data Analysis using iloc Function

## About the Project
This project demonstrates the use of Pandas iloc function for accessing patient data by index position. The dataset contains patient details from different cities in Telangana.

## Dataset Information
The dataset includes 10 patient records with following columns:
- Patient_ID: Unique ID (P101 to P110)
- Age: Age of patients (29 to 73)
- City: Hyderabad, Warangal, Vijayawada, Nizamabad, Karimnagar
- Surgery_Type: Cholecystectomy, CABG, Appendectomy, Hernia Repair, Knee Replacement, PTCA
- Operation_Duration_Min: Duration of operation in minutes
- Length_of_Stay_Days: Hospital stay duration
- Admission_Type: Planned / Emergency

## What is iloc?
iloc stands for integer location. It is used to select rows and columns by their integer index position.

Syntax: df.iloc[row_index, column_index]

## Technologies Used
- Python
- Pandas
- Git & GitHub
- VS Code

## Features / Examples Covered
1.  Select first 3 rows: df.iloc[0:3]
2.  Select specific row: df.iloc[5]
3.  Select specific cell: df.iloc[2, 1] (3rd row, 2nd column)
4.  Select multiple rows & columns: df.iloc[0:5, 0:3]
5.  Last 2 rows: df.iloc[-2:]

## How to Run
1.  Install Python
2.  Install Pandas: pip install pandas
3.  Clone this repo
4.  Run: python "iloc function.py"

## Author
Shweta Nimkar - Learning Data Analysis with Python
