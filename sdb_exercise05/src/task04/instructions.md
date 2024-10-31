# Task 5.4: Creating a Superhero Game

## a) Methods in  different classes
Objective:** In this task, you'll create a simple Java program that simulates a superhero game. You'll control 
the 
actions of a superhero, "Spider-Man," including taking damage, using web shots, and healing. This exercise will help 
you learn about Java methods and parameter passing.

1. Create a Java class called `Superhero`.
2. Inside the `Superhero` class, create static fields for the superhero's name, hit points, and web shot count.
3. Write a static method within the `Superhero` class to create the superhero. This method should take the 
   superhero's name as an input parameter and set it as the superhero's name.
4. Add another static method that displays the superhero's name, hit points, and web shot count.
5. Create a static method that simulates the superhero `taking damage`. It should reduce the hit points by an amount 
   specified as an input parameter.
6. Implement a method that allows the superhero to `use a web shot`. Decrease the web shot count with each use.
7. Write a static method that allows the superhero to `heal` by a specified amount, increasing their hit points.
8. Create a separate Java class called `SuperheroGame`.
9. In the SuperheroGame class:
   - Create an instance of the superhero, e.g., "Spider-Man," using the `createSuperhero` method.
   - Display the superhero's initial status using the `displayStatus` method.
   - Simulate various actions such as taking damage, using web shots, and healing.
10. Tell a Story: As you perform actions (taking damage, using web shots, and healing), add story contexts to make the 
     game more engaging and narratively interesting by adding print statements into your methods.

The following task gives an extension to the super hero game by including the recursive method from the previous task.

## b) Optional Story Enhancement: "Superhero's Math Challenge"

In the superhero game, Spider-Man faces a unique challenge as he encounters a villain who is controlling a mysterious device. The device presents mathematical puzzles that Spider-Man must solve to disable it and save the day.

**Objective:** Spider-Man needs to calculate factorials of certain numbers to unlock the device's secrets and stop the 
villain's evil plan.

Implementation:

When Spider-Man faces the device, the game can present a series of challenges where the villain sets different numbers to calculate factorials for. The player, controlling Spider-Man, is prompted to input a positive integer.

Spider-Man, being both a superhero and a math whiz, uses his math skills to calculate the factorials of the provided numbers. He calls the calculateFactorial method to solve each puzzle.

For each successful calculation, the device's control weakens, and Spider-Man gets closer to stopping the villain.

If the player correctly calculates the factorials for all the numbers presented by the villain, Spider-Man defeats the villain and saves the day.

### Sample output for correct calculations:
```java
Spider-Man faces a villain with a math challenge!
        The villain presents a series of numbers, and Spider-Man must calculate their factorials to stop the device.
        Calculate the factorial of 5: 120
        Calculate the factorial of 7: 5040
        Calculate the factorial of 10: 3628800
        Congratulations! Spider-Man solved the math challenge and defeated the villain!
        Superhero Name: Spider-Man
        Hit points: 100
        Web Shots: 5
```

### Sample output for incorrect calculations:
```java
Spider-Man faces a villain with a math challenge!
The villain presents a series of numbers, and Spider-Man must calculate their factorials to stop the device.
Calculate the factorial of 5: 33
Oops! That's not correct.
The villain's device remains active. Try again!
Superhero Name: Spider-Man
Hit points: 100
Web Shots: 5
```
