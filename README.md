# Simple Calculator Application

This is a basic console-based **Simple Calculator** written in Java. The calculator allows users to perform simple arithmetic operations such as addition, subtraction, multiplication, and division between two numbers. 

## Features

- Supports four basic operations: 
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)
- Simple user interface through the command line.
- Input validation for division by zero and invalid operators.

## How to Use

### Prerequisites
- **Java Development Kit (JDK)**: Ensure that you have Java installed on your machine. You can download the latest version of the JDK [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

### Steps to Run
1. **Clone the repository** (if applicable) or download the source code.
   
   ```bash
   git clone <repository-link>
   ```

2. **Compile the code** using the terminal/command line. Navigate to the directory where `SimpleCalculator.java` is located and run:
   
   ```bash
   javac SimpleCalculator.java
   ```

3. **Run the application** using the following command:
   
   ```bash
   java SimpleCalculator
   ```

4. The program will prompt you to:
   - Enter the first number.
   - Enter an operator (`+`, `-`, `*`, `/`).
   - Enter the second number.

5. The result of the operation will be displayed in the console.

### Example

```bash
Enter first number: 15
Enter an operator (+, -, *, /): *
Enter second number: 3
Result: 45.0
```

## Code Explanation

The program takes two numbers and an arithmetic operator as input from the user. Based on the operator, it performs the corresponding arithmetic operation and prints the result. It includes error handling for invalid operators and division by zero.

- **Addition (`+`)**: Adds the two numbers.
- **Subtraction (`-`)**: Subtracts the second number from the first.
- **Multiplication (`*`)**: Multiplies the two numbers.
- **Division (`/`)**: Divides the first number by the second number if the second number is non-zero. Otherwise, it displays an error message.

## Error Handling

- **Invalid Operator**: The program checks if the entered operator is one of the valid operators (`+`, `-`, `*`, `/`). If the operator is invalid, an error message is displayed, and the program exits.
- **Division by Zero**: If the user tries to divide by zero, the program outputs an error message and prevents the calculation.

## Contribution Guidelines

If you'd like to contribute to this project:
1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Submit a pull request with a detailed explanation of your changes.

## Contact

For any issues or questions regarding the calculator, feel free to contact the project maintainer.

