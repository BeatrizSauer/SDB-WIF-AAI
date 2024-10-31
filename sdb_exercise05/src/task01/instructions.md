# Task 5.1: Calculating Shipping Costs

The ShippingCostCalculator class listed below computes and prints the shipping cost for 3 different items based on their
weight. The cost is 9.95 if the item weighs less than 15.0, otherwise the cost is 12.95. While the if-else statements
are not identical due to the different variables names (weight1 vs weight2 vs weight3, cost1 vs cost2 vs cost3), each
tests the weight and assigns the cost in the same way.

```java
public class ShippingCostCalculator {

    public static void main(String[] args) {

        double weight1, weight2, weight3;
        double cost1, cost2, cost3;

        weight1 = 22.0;
        weight2 = 10.0;
        weight3 = 12.0;

        //calculate cost for item#1
        if (weight1 < 15.0) {
            cost1 = 9.95;
        } else {
            cost1 = 12.95;
        }
        System.out.println(cost1);

        //calculate cost for item#2
        if (weight2 < 15.0) {
            cost2 = 9.95;
        } else {
            cost2 = 12.95;
        }
        System.out.println(cost2);

        //calculate cost for item#3
        if (weight3 < 15.0) {
            cost3 = 9.95;
        } else {
            cost3 = 12.95;
        }
        System.out.println(cost3);

    }
}
```

Goal: Eliminate the redundant code by adding a new method to compute and print the cost based on item weight.

- Update the program to add a new method `calculateShipping` that has one input parameter for `weight`. The method will need a local variable for `cost`. The method should test the weight and print the corresponding cost.

- Update the main method to replace the existing code with 3 calls to `calculateShipping`, each passing an actual
  value for weight. The main method will no longer need local variables.

- Confirm that your new version of the program produces the same output as the original version.

```java
12.95
9.95
9.95
```