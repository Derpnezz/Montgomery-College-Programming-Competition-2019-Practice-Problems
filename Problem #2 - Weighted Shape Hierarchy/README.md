# Problem #2: Weighted Shape Hierarchy

Write an abstract class `WeightedShape` that contains one private instance integer variable
weight and one private class (static) integer variable `totalWeight`. It should contain a
constructor that is supplied with the weighting value that indicates the importance of the shape
and initializes the instance variable `weight` with the value of that parameter and adds that weight
to the class variable `totalWeight`. It should also have an abstract method named `perimeter` that
returns a `double` value, and a public method `weightedPerimeter` that returns the product of the
weight of that shape times its perimeter. In addition it should have a class (static) method that
returns the total weight of all shapes that have been created.

It should have two subclasses. The first subclass, `Rectangle`, should have two instance variables
that contain the width and height of the rectangle. The second subclass, `Circle`, should have one
instance variable that contains the diameter of the circle. Each one should have a constructor that
that is supplied with the weight and values necessary to initialize the other instance variables.
Each subclass should also override the abstract method `perimeter` computing and returning the
rectangle’s perimeter in the case of the `Rectangle` class and computing and returning the circle’s
circumference for the `Circle` class.

A third class should contain the main method, which contains the following array:
```
WeightedShape[] shapes = {new Circle(2, 4.5),
    new Rectangle(1, 1.0, 5.6), new Circle(1, 3.5)};
```
The main method should also contain a for-each loop that iterates through the array to compute
the total weighted perimeter of all the shapes and then compute and display the weighted average
in 3 decimal places. The output should be as follows:
```
Weighted average perimeter = 13.117
```