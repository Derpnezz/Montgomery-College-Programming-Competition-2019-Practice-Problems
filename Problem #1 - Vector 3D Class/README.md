# Problem #1: Vector3D Class
Write a class `Vector3D` that contains three instance variables `x`, `y` and `z` of type `double`. Provide
a constructor that accepts the values of `x`, `y` and `z` and initializes the corresponding instance
variables with those values. Provide a public method named `length` that computes and returns
the length of the vector by computing the distance between the point whose coordinates are `x`, `y` and `z` and the origin. The class `Vector3D` should implement the predefined interface `Comparable`
and consequently override the method `compareTo` that compares two vectors according to their
lengths by calling the method `length`.

In addition, it should override the `toString` method so it formats a vector as follows `(x, y, z)`.

A second class should contain the main method. It should read in vectors from a file named
`vectors.txt` that contains at most 20 vectors. It should determine the vector with the greatest
length and display that vector and its length. If the file contains two such vectors it should
display the first one.

Given the following input file that contains one vector per line:
```
10.5 7.4 10.4
6.3 5.8 11.8
13.6 9.3 12.7
6.3 8.3 2.9
11.5 12.6 3.9
9.3 12.7 13.6
10.3 2.5 8.3
```
The program should produce the following output:

```
Longest vector is (13.6, 9.3, 12.7) of length 20.802
```

`Notes: Use the following formula to calculate the length of the vector:
Square root of (x2 + y2 + z2)`