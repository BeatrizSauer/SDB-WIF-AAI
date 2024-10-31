# Task 6.5: Intersection

Create a class `Intersection` and add a method `intersection` to the class, which takes two int arrays as arguments, and returns an int array which contains the numbers that occur in both arrays (*from Mathematics - set theory: intersection*).
Also, write a `main` method in which you test the intersection method using some given examples:
-	{0, 1, 2, 3, 4, 5} and {3, 4, 5, 6, 7, 8} -> {3, 4, 5}         (set1a, set1b)
-	{0, 1, 2, 3} and {4, 5, 6} -> {}			  (set2a, set2b)
-	{0, 1, 2}, {0, 1, 2} -> {0, 1, 2}			  (set3a, set3b)

**Note:**
-	You need a `main()` and an `intersection()` method
- main():
  - In this task, you don’t have to read values from the keyboard, a predefined test is sufficient. 
  - You should generate 6 arrays as specified above.
  - Here you call the method `intersection()` and pass the arrays you want to check for an intersection.
  - You can use the following printouts for output:
```java
System.out.println(Arrays.toString(intersection(set1a, set1b)));
System.out.println(Arrays.toString(intersection(set2a, set2b)));
System.out.println(Arrays.toString(intersection(set3a, set3b)));

```

- intersection():
  - Because the size of arrays is fixed after creation, you must determine the intersection twice: once to find the 
       size that is used to create the return array, and once to insert the values.
  - 1st for-loop: find the number of intersection elements
  - Create the array of the size determined in the 1st loop.
  - 2nd for-loop: populate the array created with the intersection elements.
