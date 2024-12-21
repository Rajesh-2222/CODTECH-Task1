CODTECH IT (Simple Calculator)

NAME : RAJESH M 

COMPANY : CodTech IT Solutions 

ID : CT08DS108

DOMAIN : PYTHON PROGRAMMING

DURATION : November 2024 - December 2024 



Overview of the Project : 

Project: SIMPLE CALCULATOR

Objective : Develop a command-line-based calculator in Python that performs basic arithmetic operations, including addition, subtraction, multiplication, and division.


Technologies used :

1. Python Programming Language: 
   Python will serve as the core language for implementing the calculator.  

2. Python Standard Library:
   No additional libraries are necessary—this calculator can be built entirely using Python's built-in functionality.  

3. Integrated Development Environment (IDE):
   Optional tools like PyCharm, Visual Studio Code, or Jupyter Notebook can be used for coding and debugging the project.  

4. Standard Input/Output (I/O):
   - `input()` function for receiving user inputs.  
   - `print()` function for displaying results and prompts to the console. 

5. Basic Control Structures: 
   - `if-elif-else` statements for choosing the desired operation.  
   - A `while` loop for enabling repeated calculations or exiting the program.  

6. Error Handling: 
   - Use of `try-except` blocks to handle invalid inputs, such as non-numeric values or division by zero.  


How the Program Works: 

1. Display Menu:
   Provide users with a menu to select their desired operation: addition, subtraction, multiplication, division, or exiting the program.  

2. Take Input:
   Prompt the user to enter two numbers (operands).  

3. Perform Calculations:  
   Based on the selected operation, execute the respective arithmetic operation.  

4. Error Checking:
   Use exception handling to manage errors such as invalid inputs or division by zero.  

5. Output Result:  
   Display the result of the calculation to the user and ask if they want to perform another operation or quit.  

 Conclusion: 
This project allows you to apply Python fundamentals such as:  
- Handling user input,  
- Using conditionals and loops for logic,  
- Incorporating error handling with `try-except`.  

It serves as a practical foundation for building more advanced applications in Python.  

 Key Components:

1. Attributes:  
   - float num1, num2`: Stores the operands (numbers input by the user).  
   - str operator: Represents the operation selected by the user (`+, -, *, /`).  

2. Constructor (optional for modular design):**  
   - SimpleCalculator(): Initializes the calculator program.  

3. Methods:  
     - performOperation(float num1, float num2, str operator):  
     - Executes the desired calculation based on the operator selected (`+`, `-`, `*`, `/`).  
     - Returns the result of the operation.  
     - `validateInput(str input)`**:  
     - Ensures the user enters valid numeric inputs and a valid operator.  

4. Error Handling:  
   - Division by zero:** Displays an error if the user attempts to divide by zero.  
   - Invalid Input:** Ensures non-numeric or invalid operator entries are managed gracefully.  


  Program Workflow:  

1. Initialization:
   - Prompt the user to enter two numbers (`num1` and `num2`) and an operator (`+`, `-`, `*`, `/`).  
   - Use error handling to validate inputs.  

2. Perform Calculation:
   - Call the `performOperation` method to execute the selected operation.  

3. Display Result: 
   - Print the result of the calculation, formatted for clarity.  

4. Repeat or Exit:  
   - Use a loop to allow the user to perform additional calculations or type "exit" to quit the program.  


Sample Execution:  

Welcome to the Simple Calculator!
Enter the first number: 12
Enter the operator (+, -, *, /): *
Enter the second number: 5
Result: 12 * 5 = 60
Would you like to perform another calculation? (yes/no): yes

Enter the first number: 8
Enter the operator (+, -, *, /): /
Enter the second number: 0
Error: Division by zero is not allowed.
Would you like to perform another calculation? (yes/no): no

Goodbye!

 
   Program Features:  

1. Error Handling:  
   - Handles invalid inputs, division by zero, and unexpected operator entries.  
2. Modular Design:  
   - Each operation and validation logic is placed into separate methods for easier maintenance and readability.  
3. User-Friendly Input and Output:  
   - Prompts and results are clear and formatted to enhance user interaction.  
4. Flexible Usage:
   - Allows users to perform multiple calculations without restarting the program.  



  Potential Enhancements:  

1. Additional Operations:  
   - Extend the calculator with operations like square roots, exponents, and modulo.  
2. History Feature:
   - Track and display the history of all calculations during the session.  
3. Enhanced Validation:  
   - Use regex for advanced input validation.  
4. GUI Support:
   - Upgrade to a graphical user interface using frameworks like Tkinter or PyQt for improved usability.  

