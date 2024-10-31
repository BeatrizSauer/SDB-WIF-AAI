# Task 5.2: Prime Number Checker

In this task, you'll write a Java program to determine if a given number is a prime number:
>A prime number is a positive integer greater than 1 that is divisible only by 1 and itself.

You will implement a method to check for primality and then test the method with various numbers.

1. Start by creating a Java class called `PrimeNumber`.
2. Write a static method within the `PrimeNumber` class named `isPrime`. This method should accept an integer as a parameter and return true if the number is prime and false if it's not.
3. Inside the `isPrime` method, create a for loop that iterates over alle the numbers from `prime-1` to `> 1`. 
     Check whether the number is divisible by the for loop counter. If yes: return false, if no, keep on going. 

## Hints:
- Use the modulo operator (%) to check for divisibility.

Testing:
After implementing the `isPrime` method, test it with various numbers to verify its correctness. Check both prime and 
non-prime numbers to ensure accurate results. Let the user provide numbers via the console.