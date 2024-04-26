# Student Attendance Record System

## Objective:
The project aims to store student IDs and their attendance status in arrays, calculate attendance percentages, and provide functionalities for updating, searching, and displaying student data.

## Input:
The program takes students' names (string), IDs (integers), and attendance status (char) for five days.

## Output:
For the search option: The program prints the ID, Name, attendance status, and attendance percentage.
For the display option: It prints all data of students stored in the system (Name – ID -attendance status – attendance percentage).

## Arrays Used:
Four 1D arrays:
- Student ID
- Attendance status
- Attendance percentage
- Name

## Subroutines:
- Two subroutines: One for update and one for search
- Display function for the search option: It takes indices of all arrays (ID, Name, Status, Percentage) as parameters and returns void after displaying the info.
- For update: It takes the start-location of the five statuses to be updated. It returns void after calculating the new percentage of the student.

## Data Storage:
- Input data is stored for percentage calculation, attendance update, data display, and manipulation.
- Name (string), ID (integers), and attendance status (char) are stored.

## Interfaces:
Beginning of the program initializes static data for display messages and initializes two counters with zero.

## Additional Information:
- The program utilizes at least four different addressing modes, branches, and iteration operations.
- All input data are utilized for further inquiries such as updating, searching, and calculating attendance percentages.

