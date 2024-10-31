# Task 5.3: Recursive Factorial Calculator

**Objective:** In this task, you will create a Java program to calculate the factorial of a given positive integer 
using a recursive method. The factorial of a number is the product of all positive integers from 1 to that number.

## Instructions:

- Create a Java Class: Start by creating a Java class called `FactorialCalculator`.
- Implement a Recursive Method: Write a static recursive method within the `FactorialCalculator` class named 
  `calculateFactorial`. This method should accept a positive integer as a parameter and return the factorial of that integer.

- Define the Base Case: In your recursive method, define the base case. The base case should be when the input is 1, 
in which case the factorial is 1.

- Recursive Case: For input greater than 1, the method should call itself recursively to calculate the factorial. The 
recursive case should be expressed as a formula using the current number and the factorial of the number one less.

- Test the Method: In the `main` method of your class, prompt the user to enter a positive integer, call the 
`calculateFactorial` method to compute the factorial, and display the result.

## Hints:

- In the recursive method, you'll need to make the method call itself with a smaller input value in each step.
- The base case is essential to terminate the recursive calls. Make sure to handle it correctly.
- To calculate the factorial, you can use the formula n! = n * (n-1)! .

## Testing:

Test the `calculateFactorial` method with various positive integers to ensure it computes the factorial correctly. For example, calculate the factorial of 5, 7, and 10.
