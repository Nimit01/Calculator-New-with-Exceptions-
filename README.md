Java Calculator  
📌 Overview  
This Java program is a menu-driven calculator that performs arithmetic operations like addition, subtraction, multiplication, division, square, cube, and square root. It uses object-oriented principles and includes custom exception handling for robust error control.

✨ Features  
Supports operations:
Addition  
Subtraction  
Multiplication  
Division (with divide-by-zero check)  
Square  
Cube  
Square Root (with negative input handling)  
User-friendly menu with input validation  
Custom exception handling for invalid inputs, unsupported operations, and arithmetic errors

📂 File Structure & Method Descriptions  

1. MainCalculator.java  
Implements:
- Menu-driven interface
- Takes user input for operation and numbers
- Calls respective operation classes

2. Addition.java  
Defines:
- add(double a, double b) ➜ Returns a + b

3. Subtraction.java  
Defines:
- subtract(double a, double b) ➜ Returns a - b

4. Multiplication.java  
Defines:
- multiply(double a, double b) ➜ Returns a * b

5. Division.java  
Defines:
- divide(double a, double b) ➜ Returns a / b  
- Handles divide-by-zero using exception

6. Square.java  
Defines:
- square(double a) ➜ Returns a²  
- Checks for overflow

7. Cube.java  
Defines:
- cube(double a) ➜ Returns a³  
- Checks for overflow

8. SquareRoot.java  
Defines:
- sqrt(double a) ➜ Returns √a  
- Throws exception if a is negative

9. CalculatorExceptions.java  
Defines custom exceptions:
- DivisionByZeroException ➜ For divide-by-zero errors  
- NegativeSqrtException ➜ For negative square root inputs  
- InvalidInputException ➜ For invalid menu or number input  
- OverflowException ➜ For arithmetic overflow  
- UnderflowException ➜ For underflow  
- OperationNotSupportedException ➜ For invalid operation choices
