NAME: HIMANSH GUNDETI
ID:CT08DS7970
DOMAIN:JAVA PROGRAMMING 
DURATION:“10TH SEP 2024 to 10TH OCT 2024” 
MENTOR:SRAVANI GOUNI

Description:

1. Importing the Scanner Class:
   - `import java.util.Scanner;`
   - The `Scanner` class is imported from the `java.util` package to allow user input through the console.

2. Main Method:
   - `public static void main(String[] args)`
   - This is the entry point of the Java application. The `main` method starts the program execution.

3. Creating a Scanner Object:
   - `Scanner scanner = new Scanner(System.in);`
   - A `Scanner` object is created to read user input from the console.

4. User Input for Numbers:
   - The program prompts the user to enter two numbers using `System.out.print()`:
     - `double num1 = scanner.nextDouble();` reads the first number from the user.
     - `double num2 = scanner.nextDouble();` reads the second number from the user.
   - The data type `double` is used to handle both integer and decimal numbers.

5. Choosing an Operation:
   - `System.out.println("Choose an operation: + (addition), - (subtraction), * (multiplication), / (division)");`
   - The program asks the user to choose one of the four arithmetic operations (addition, subtraction, multiplication, division).
   - The input is taken as a single character using `scanner.next().charAt(0);`, which reads the first character of the user input.

6. Switch Case for Operation:
   - A `switch` statement is used to handle the different arithmetic operations based on the user's input:
     - `case '+':` performs addition.
     - `case '-':` performs subtraction.
     - `case '*':` performs multiplication.
     - `case '/':` performs division but also checks for division by zero.
   
7. Division by Zero Check:
   - Inside the division case, a check is added to ensure that the second number (`num2`) is not zero:
     - `if (num2 != 0)` ensures that division by zero does not occur, which would otherwise cause a runtime error.
     - If the user attempts to divide by zero, an error message is displayed: `"Error: Cannot divide by zero."`

8. Invalid Operation Handling:
   - If the user enters an operation other than the valid choices (`+`, `-`, `*`, `/`), the program displays an error message: `"Error: Invalid operation."`
   - The program exits the `main` method without proceeding further by using the `return` statement.

9. Displaying the Result:
   - After performing the selected operation, the program prints the result to the console:
     - `System.out.println("The result is: " + result);`

10. Closing the Scanner:
    - `scanner.close();`
    - The `scanner` is closed to release the resources used for reading user input.

Conclusion:
The provided Java program is a simple and efficient calculator that enables users to perform basic arithmetic operations—addition, subtraction, multiplication, and division—based on their inputs. It demonstrates essential programming concepts such as:

User input handling using the Scanner class.
Control flow through conditional structures like the switch statement.
Error handling by preventing division by zero.
Output:
![image](https://github.com/user-attachments/assets/745f046d-6544-4611-a9e4-d36416d34472)
