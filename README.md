
# Bank Account Simulation
# Python OOP Projects
This repository contains a simple Python project simulating a bank account (`bankacc.ipynb`). It demonstrates fundamental Object-Oriented Programming (OOP) concepts in Python.
This repository contains Python Jupyter Notebook projects demonstrating fundamental Object-Oriented Programming (OOP) concepts.
## Description
---
The project consists of a Python Jupyter Notebook that defines an `Account` class (Compte Bancaire). The class allows you to manage a bank account with basic operations such as:
## 1. Advanced Calculator (`py_project.ipynb`)
### Description
This project features a Python Jupyter Notebook that defines a `Calculator` class. It provides an interactive command-line interface to perform both basic and advanced mathematical operations. The calculator's architecture makes it easily extensible for adding new mathematical functions dynamically.
### Features
- **Extensible Architecture**: Uses a dictionary to store operations, allowing the addition of new functions dynamically via the `add_operation` method.
- **Basic Operations**: Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
- **Advanced Operations**: Exponentiation (`**`), Square Root (`sqrt`), and Logarithm (`log`).
- **Interactive Menu**: A text-based user interface that continuously prompts for input until you decide to quit (`q`).
- **Error Handling**: Gracefully handles invalid inputs such as non-numeric values and unknown operations.
### How to Run
1. Make sure you have Python and [Jupyter Notebook](https://jupyter.org/) installed.
2. Clone this repository or download the `py_project.ipynb` file.
3. Open a terminal or command prompt and navigate to the folder containing the file.
4. Run `jupyter notebook` or `jupyter lab` to open the notebook interface in your browser.
5. Open `py_project.ipynb` and run the cell to start the interactive calculator.
### Code Example
```python
# Create the calculator instance
calculator = Calculator()
# Add an advanced operation (e.g., Exponentiation)
def exponentiation(a, b):
    return a ** b
calculator.add_operation("**", exponentiation)
# Perform a calculation
