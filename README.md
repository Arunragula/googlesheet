# googlesheet
Spreadsheet Web Application
Overview
This project is a web-based spreadsheet application that allows users to create, edit, and manipulate tabular data. It provides an interactive UI with functionalities similar to traditional spreadsheet software.

🔗 Live Demo: https://arunragula.github.io/googlesheet/
![image](https://github.com/user-attachments/assets/b30f887f-bac1-4b55-b8c4-8294322cfad4)

#Tech Stack
The project is built using the following technologies:

HTML (index.html): Provides the structure of the web application, including the toolbar, formula bar, and spreadsheet grid.
CSS (style.css): Handles the styling of the spreadsheet, including UI elements like cells, toolbars, and dialogs.
JavaScript (script.js): Implements core spreadsheet functionalities like cell selection, input handling, formula evaluation, and event listeners.

Data Structures Used:
1.Grid Representation (2D Array)

The spreadsheet grid is stored as a JavaScript object where each cell is represented using a key-value pair ({row, col} as the key and the cell’s value as the data).
Example:
{
  "A1": "Hello",
  "B2": "123",
  "C3": "=SUM(A1:B2)"
}

2.Event Listeners
Handles user interactions like clicking a cell, entering data, or resizing columns/rows.
Uses addEventListener to capture clicks, keypresses, and other user actions.

3.CSS Variables
Defines color schemes, layout, and appearance settings using :root variables for easy customization.

4.Formula Parsing
Implements a basic formula engine that evaluates expressions like =SUM(A1:B2).
Parses values dynamically to update dependent cells.

Why This Tech Stack?
JavaScript (Vanilla JS): Provides dynamic interactions without requiring external libraries.
CSS (Custom Styling): Allows for a clean, minimalistic spreadsheet UI with adjustable themes.
HTML (Semantic Markup): Ensures structured content for better accessibility and maintainability.

Features
✔️ Add/Delete Rows & Columns
✔️ Formula Bar for Calculations
✔️ Cell Formatting (Bold, Italic, Font Size)
✔️ Chart Creation
✔️ Save & Load Sheet Data

Future Enhancements
Support for advanced formulas and functions.
Export and import functionality.
Integration with cloud storage for saving sheets.
