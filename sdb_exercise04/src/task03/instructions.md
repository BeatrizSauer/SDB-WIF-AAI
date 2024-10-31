# Task 4.3: Loops, loops, loops

We want to understand the logic of loops. To do this, we will learn how while and for loops are defined and we will understand when which loop is used.

Here is an example of a while loop:
```java
public class TestLoop
{
    public static void main(String[] args)
    {
        int x = 5;
        while (x > 0)
        {
            System.out.println(x);
            x = x - 1;
        }
    }
}
```
- What is printed to the console?

A while loop can be expressed by a for loop:

```java
public class TestLoop
{
    public static void main(String[] args)
    {
        for (int x = 5; x > 0; x = x - 1)
            System.out.println(x);
    }
}
```
### Note: 
>In a for loop you declare and initialize the variable(s), specify the condition, and specify how the loop variable
> (s) change in the header of the for loop as shown below.

Now it is your turn:

1. Rewrite the following code to use a while loop instead of a for loop to print out the numbers from 1 to 10 (inclusive).
```java
public class TestLoop
{
    public static void main(String[] args)
    {
        for (int x = 1; x <= 10; x++)
            System.out.println(x);
    }
}
```

2. Rewrite the following code so that it uses a for loop instead of a while loop to print out all the integers from 5 to 15 (inclusive).
```java
public class TestLoop
{
    public static void main(String[] args)
    {
        int x = 5;
        while (x <= 15)
        {
            System.out.println(x);
            x = x + 1;
        }
    }
}
```

3. Rewrite the following code to use a while loop instead of a for loop to print out the numbers from 10 to 100 by 10’s (inclusive).
```java
public class TestLoop
{
    public static void main(String[] args)
    {
        for (int x = 10; x <= 100; x=x+10)
            System.out.println(x);
    }
}
```

4. The following code should print the values from 1 to 10 (inclusive) but has errors. Fix the errors so that the 
   code works as intended. If the code is in an infinite loop you can stop the code execution by hitting the red 
   rectangular box within your IDE.
```java
public class TestLoop
{
    public static void main(String[] args)
    {
        int x = 1;
        while (x < 10)
        {
            System.out.println(x);
        }
    }
}
```
5. The following code should print the values from 10 to 5, but it has errors. Fix the errors so that the code works as intended.

```java
public class TestLoop
{
    public static void main(String[] args)
    {
        for (int x = 10; x >= 5; x--)
        {
           System.out.println(x);
           x--;
        }

    }
}
```
6. The following code should print the values from 10 to 1, but it has errors. Fix the errors so that the code works as intended.
```java
public class TestLoop
{
    public static void main(String[] args)
    {
        int x = 10;
        while (x >= 0)
        {
           x--;
           System.out.println(x);
        }
    }
}
```

7. Finish the code below to print the values for 10 * x where x changes from 0 to 10 using a loop.
```java
public class TestLoop
{
    public static void main(String[] args)
    {

    }
}
```

8. Write the code below to print a rectangle of stars (*) with 5 rows of stars and 3 stars per row. Hint: use nested 
for loops.
```java
public class TestLoop
{
    public static void main(String[] args)
    {
    }
}
```

9. Write the code below to print a rectangle of stars (*) with 3 rows of stars and 5 stars per row.
```java
public class TestLoop
{
    public static void main(String[] args)
    {
    }
}
```

10. Write the code below to print 55555, 4444, 333, 22, 1 with each on a different line.
```java
public class TestLoop
{
    public static void main(String[] args)
    {
    }
}
```

11. Write a program to draw a square shape on the console using `#`:
- Choose a random number from 0-100 (i.e. through user input)
- Loop and print `#` to the console.
- Print out something like “You got it!” and ask whether the task should be repeated.
