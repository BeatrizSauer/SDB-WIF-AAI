# sdb_exercise03

In this exercise, you will learn the following:
- [Task 3.1](src%2Ftask01%2FInstructions.md): Temperature conversion application
- [Task 3.2](src%2Ftask02%2FInstructions.md): VAT calculator
- [Task 3.3](src%2Ftask03%2FInstructions.md): Satellite time
- [Task 3.4](src%2Ftask04%2FInstructions.md): Circumference calculation and user output

In this exercise we will look at writing small applications. The main focus is on calculating with variables, i.e. formulating expressions and saving the results in variables.

Furthermore, we will interact with the user. You have already learned that you can produce output in the console 
window with `System.out.println()`. However, you can also read user input from the console. To do this, you will 
learn about the `Scanner` class - a class provided by the Java Framework.

Whenever you are dealing with Java classes of the framework, you should look in the **API - the Application 
Programming Interface**.

The API documentation is made available to you online.

Here are a few helpful links to the API documentation:
Scanner: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/Scanner.html

Integer: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html

Double: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html

Math: https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Math.html

The API of a specific class lists all the methods and attributes of the classes and shows how to use the given 
classes and methods.

Here a few highlights:

```java
// creating a random numer between 0 and 10
Math.random()
// creating a scanner object to read console input
Scanner  sc = new Scanner();
int i = sc.nextInt();

// using the Integer class to read in an integer from the command window
int i = Integer.parseInt(sc.next());

// using the Double class to read in a double from the command window
double d = Double.parseDouble(sc.next());
```

Have fun!