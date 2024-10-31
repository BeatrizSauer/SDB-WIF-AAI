# Task 4.4: Guessing Game

In the guessing game, the computer picks a random number from 0-100 and you have to guess it. After each guess, the
computer will give you clues like “Too high” or “Too low”. Here’s the pseudocode for the guessing game. Pseudocode is an
English description or plan of what your code will do step by step. What’s the loop variable for this program? Can you
identify the 3 steps of writing this loop with respect to the loop variable?

1. Choose a random number from 0-100
2. Get the first guess
3. Loop while the guess does not equal the random number,
    - If the guess is less than the random number, print out “Too low!”
    - If the guess is greater than the random number, print out “Too high!”
    - Get a new guess (save it into the same variable)
4. Print out something like “You got it!”

As an extension to this project, you can add a counter variable to count how many guesses the user took and print it out
when they guess correctly.

When you finish and run your program, what is a good guessing strategy for guessing a number between 0 and 100? What was
your first guess?
> One great strategy is to always split the guessing space into two and eliminating half, so guessing 50 for the
> first guess. This is called a divide and conquer or binary search algorithm. If your guess is between 0-100, you
> should be able to guess the number within 7 guesses. Another extension to this challenge is to test whether the user got
> it in 7 guesses or less and provide feedback on how well they did.
