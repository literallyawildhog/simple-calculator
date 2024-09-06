# Simple-Calculator

**Simple-Calculator** is a basic Python script designed to perform fundamental arithmetic operations: addition, subtraction, multiplication, and division. Developed using Visual Studio, this project features a simple command-line interface that allows users to perform calculations interactively.

## Features

- **Addition**: Performs addition of two numbers.
- **Subtraction**: Performs subtraction of two numbers.
- **Multiplication**: Performs multiplication of two numbers.
- **Division**: Performs division of two numbers with error handling for division by zero.
- **Interactive Command-Line Interface**: Prompts users to choose an operation and enter numbers.

## Getting Started

### Prerequisites

- **Visual Studio** with Python support installed.
- Python 3.9

### Installation

1. **Clone the repository** or **download** the code:
   ```bash
   git clone https://github.com/literallyawildhog/simple-calculator.git
   ```

2. **Open Visual Studio** and **load the project**:
   - Launch Visual Studio.
   - Go to `File` > `Open` > `Project/Solution` and select the `simple-calculator` folder.

3. **Set up the Python environment**:
   - Ensure that you have Python 3.x installed and configured in Visual Studio.
   - Configure the Python environment by going to `Tools` > `Options` > `Python Environments`.

4. **Run the script**:
   - Open the `simplecalculator.py` file in Visual Studio.
   - Press `F5` or click the `Start` button to run the script.

### Usage

- After running the script, follow the prompts:
  - **Select operation**: Choose between addition, subtraction, multiplication, or division.
  - **Enter numbers**: Input the two numbers you wish to operate on.
  - **Result**: The result of the operation will be displayed.
  - **Continue**: You will be asked if you want to perform another calculation.

### Example

```bash
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice (1/2/3/4): 1
Enter first number: 10
Enter second number: 5
The result is: 15.0
Do you want to perform another calculation? (yes/no): no
```

### Code Overview

The script includes the following functions:
- `add(x, y)`: Returns the sum of `x` and `y`.
- `subtract(x, y)`: Returns the difference between `x` and `y`.
- `multiply(x, y)`: Returns the product of `x` and `y`.
- `divide(x, y)`: Returns the quotient of `x` and `y`, with error handling for division by zero.
