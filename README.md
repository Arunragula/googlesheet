# googlesheet
Spreadsheet Web Application 
Overview
This project is a web-based spreadsheet application that allows users to create, edit, and manipulate tabular data. It provides an interactive UI with functionalities similar to traditional spreadsheet software.

🔗 Live Demo: https://arunragula.github.io/googlesheet/
![image](https://github.com/user-attachments/assets/b30f887f-bac1-4b55-b8c4-8294322cfad4)

 ## Table of Contents
- `✨ Features`
- `🛠 Tech Stack`
- `⚙️ Implementation Details`
- `📥 Installation`
- `🚀 Usage`
- `🔮 Future Enhancements`
- `🤝 Contributing`
- `📜 License `
## Features
- `➕ Add or delete rows and columns dynamically.`
- `🧮 Formula bar for real-time calculations  ```(e.g., =SUM(A1:B2)). ````
- `🎨 Cell formatting options: bold, italic, and font size adjustments.`
- `📊 Basic chart creation for data visualization.`
- `💾 Save and load spreadsheet data locally.`
## Tech Stack
The application is built using a minimalist, modern web development stack:

- ` HTML (index.html) → Structures the UI (toolbar, formula bar, grid).`
 - `CSS (style.css) → Styles the app with a clean, responsive design.`
 - `JavaScript (script.js) → Drives interactivity, formula evaluation, and event handling.`
## Why This Stack?
- `✔Vanilla JavaScript → Ensures dynamic functionality without external dependencies.`
- `✔ Custom CSS → Provides a minimalistic, customizable UI.`
- `✔ Semantic HTML → Enhances accessibility and maintainability.`

## Implementation Details
📊 Grid Representation
- `Uses a JavaScript object to store grid data as key-value pairs:`
```json
{ "A1": "Hello", "B2": "123" }
```

## Event Listeners
 Handles user actions (clicks, keypresses) using addEventListener for seamless interaction.
 - `CSS Variables`
Uses :root variables for reusable styling (colors, layouts).
- `📜 Formula Parsing`
Includes a lightweight engine to evaluate formulas and update dependent cells dynamically.
- `📥 Installation`
To run the project locally:

## 1.Clone the repository:

```bash
git clone https://github.com/arunragula/googlesheet.git
```
## Navigate to the project directory:

```bash
cd googlesheet
```
## Open index.html in a web browser:

Use a local server (e.g., live-server in VS Code) for the best experience.
 No additional dependencies required!

## Usage
- `Open the application in your browser via the live demo or local setup.`
- `Click cells to select and input data or formulas (e.g., =SUM(A1:B2)).`
- `Use the toolbar to format cells (bold, italic) or add charts.`
- `Add/Delete rows and columns as needed.`
- `Save your work locally and reload it later.`
## Future Enhancements
## Planned upgrades to take the project to the next level:

- `✔ Advanced Formulas → Support for complex functions like IF, VLOOKUP.`
- `✔ Export/Import → Options to export/import data as CSV or Excel files.`
- `✔ Cloud Integration → Connect to services like Google Drive for persistent storage.`
- `✔ Enhanced UI/UX → Themes, shortcuts, and collaborative features.v

🤝 Contributing
Contributions are welcome! To get started:

## 1️⃣ Fork the repository.
## 2️⃣ Create a new branch:

```bash
git checkout -b feature/your-feature-name
```
## 3️⃣ Make your changes and commit:

```bash
git commit -m "Add your message here"
```
## 4️⃣ Push to your branch:

```bash

git push origin feature/your-feature-name
```
## 5️⃣ Submit a pull request.

## 📝 Follow the Code of Conduct (CODE_OF_CONDUCT.md) (to be added).
Ensure your code adheres to the project’s style.

