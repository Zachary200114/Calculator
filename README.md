## Simple Python Calculator

This is a **Simple Python Calculator** that performs basic arithmetic operations, including addition, subtraction, multiplication, and division. The user interacts with the calculator through a console-based interface.

## Features

- ➕ **Addition** – Add two numbers.
- ➖ **Subtraction** – Subtract one number from another.
- ✖️ **Multiplication** – Multiply two numbers.
- ➗ **Division** – Divide one number by another with error handling for division by zero.
- ❌ **Quit Option** – Exit the calculator when done.

## Requirements

Ensure you have Python installed on your computer. To check your Python version, run:

```bash
python --version
```

## How to Run

1. Copy the code into a `.py` file, for example: `calculator.py`.

2. Open a terminal in the same directory as the file.

3. Run the program with:

```bash
python calculator.py
```

4. Follow the on-screen instructions:
   - Choose an operation (1-4).
   - Enter the two numbers for the calculation.
   - Enter `5` to quit the calculator.

## 🖱️ Example Usage

```
PICK WHAT OPERATION YOU WANT TO DO:
1. Subtract
2. Add
3. Multiply
4. Division
5. Quit Calculator

Enter your choice: (1/2/3/4/5): 2
Enter first number: 10
Enter second number: 5
10.0 + 5.0 = 15.0
```

If you attempt division by zero:

```
Enter your choice: (1/2/3/4/5): 4
Enter first number: 10
Enter second number: 0
10.0 / 0.0 = ERROR
```

## Customization

- Add more complex operations by defining new functions.
- Update the menu options in the `Calculator()` function.

## Known Issues

- Invalid input (non-numeric) for numbers will raise an error.
- If the user chooses an invalid option, the program ends immediately instead of looping.

## Suggestions For Improvement 
-If anyone has any ideas that I can improve on, please feel free to reach out.
