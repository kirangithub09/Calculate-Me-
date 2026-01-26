# Calculate Me! 🧮

A sleek, functional, and responsive web-based calculator built using **HTML5**, **CSS3**, and **Vanilla JavaScript**. This project features a clean UI and utilizes a utility-first CSS approach for a structured layout.

🚀 Live Demo


## 🚀 Features

* **Mathematical Operations:** Performs addition, subtraction, multiplication, and division.
* **Expression Handling:** Supports percentage calculations and parentheses for complex expressions.
* **Clear Functionality:** A dedicated 'C' button to reset the calculation string instantly.
* **Responsive Layout:** Built with a custom utility-based Flexbox system to ensure it stays centered and aligned.
* **Modern Typography:** Integrated with Google Fonts (Hind Siliguri, Poppins, and Ubuntu).

## 🛠️ Technologies Used

* **HTML5:** Semantic structure for the calculator interface.
* **CSS3:** Custom styling including `utils.css` for reusable layout classes.
* **JavaScript (ES6):** Logic for event handling and expression evaluation.

## 📂 Project Structure

```text
├── index.html   # The main structure of the calculator
├── style.css    # Specific styling for buttons and input fields
├── utils.css    # Utility classes for flexbox, alignment, and margins
└── script.js    # Logic for calculations and DOM manipulation
```
⚙️ How It Works
Event Listeners: The script selects all elements with the .button class and attaches a click event listener.

String Concatenation: Every button click appends the character to a local string variable.

Evaluation: Upon clicking =, the JavaScript eval() function calculates the result of the string and displays it in the input field.

Reset: Clicking C clears the string and resets the display.
