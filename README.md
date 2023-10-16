# C++ Basics: Hello World and Basic Operations

This repository contains examples and explanations of the basics of C++ programming, including printing "Hello, World!" and performing basic operations. This README provides an overview of how to get started with C++ programming.

## Table of Contents
- [C++ Basics](#c-basics)
  - [Hello, World!](#hello-world)
  - [Basic Operations](#basic-operations)
- [Examples](#examples)

## C++ Basics

### Hello, World!

Printing "Hello, World!" is a common starting point in C++ programming. You can achieve this using the `cout` object from the `iostream` library:

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```
### **ALGORITHM**
1.#include <iostream>: This line includes the Input/Output Stream library, which provides functions like cout and endl for input and output operations.

2.int main() { ... }: This is the main function of your C++ program. It is the entry point of your program, and execution begins here.

3.std::cout: This is the standard C++ output stream, which is used to display output on the console.

4."Hello, World!": This is the text you want to print. It is enclosed in double quotation marks to represent a string.

5.<<: This is the output stream operator, used to insert the string "Hello, World!" into the std::cout stream.

6.std::endl: This is used to insert a newline character and flush the output buffer. It ensures that "Hello, World!" is displayed on a new line.

7.return 0;: This line indicates the successful completion of the main function. In C++, it's a convention to return 0 to indicate a successful execution of the program.

8. Compile and run this code, and it will print "Hello, World!" to the console.
   
### **OUTPUT**





![Hello world](https://github.com/Purvansha022609/Basic/assets/139473344/17549f53-8c30-4869-8284-b26c5f601d7f)

### Basic Operations

C++ supports various basic operations, including arithmetic operations, variable declaration, and assignment. Here are some examples:

```cpp
#include <iostream>

int main() {
    // Variable declaration and initialization
    int x = 10;
    int y = 5;

    // Arithmetic operations
    int sum = x + y;
    int difference = x - y;
    int product = x * y;
    int quotient = x / y;
    int remainder = x % y;

    // Output the results
    std::cout << "Sum: " << sum << std::endl;
    std::cout << "Difference: " << difference << std::endl;
    std::cout << "Product: " << product << std::endl;
    std::cout << "Quotient: " << quotient << std::endl;
    std::cout << "Remainder: " << remainder << std::endl;

    return 0;
}
```


### **ALGORITHM**
1.Start the program.

2.Display a menu to the user with options for different arithmetic operations (e.g., addition, subtraction, multiplication, division). Each option should be associated with a unique numeric code (e.g., 1 for addition, 2 for subtraction, etc.).

3.Prompt the user to enter the numeric code corresponding to the desired operation.

4.Read and store the user's choice.

5.Prompt the user to enter the first number for the calculation and store it in a variable (e.g., num1).

6.Prompt the user to enter the second number for the calculation and store it in another variable (e.g., num2).

7.Use a switch statement to perform the appropriate arithmetic operation based on the user's choice:

8.If the user's choice is 1, add num1 and num2 and store the result in a variable (e.g., result = num1 + num2).

9.If the user's choice is 2, subtract num2 from num1 and store the result in result.

10.If the user's choice is 3, multiply num1 and num2 and store the result in result.

11.If the user's choice is 4, check if num2 is not equal to zero. If it's not, divide num1 by num2 and store the result in result. If num2 is zero, display an error message indicating that division by zero is not allowed.

12.Display the result of the calculation to the user.

13.Ask the user if they want to perform another calculation or exit the program.

14.If the user chooses to perform another calculation, return to step 3. If the user chooses to exit, end the program.

15.End the program.

This algorithm outlines the basic structure of a calculator program using switch cases. It allows the user to choose an operation, enter two numbers, perform the calculation, and display the result. Additionally, it includes error handling for division by zero and provides the option to perform multiple calculations or exit the program.

### **OUTPUT**

![Basic calculator](https://github.com/Purvansha022609/Basic/assets/139473344/5b35e14c-03b6-484c-bf39-d34b003e715d)
