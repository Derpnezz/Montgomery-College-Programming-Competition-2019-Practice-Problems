# Problem #6 (Tie-Breaker): Sort Ragged Array

Write a method called sort7thRaggedArray that takes a 2D ragged array.
The method will return a new sorted ragged array based on the following rule.
The rows should be sorted according to the sum of each element which is divisible by 7 in the
ascending order.

The following is a sample run of this program:
```
Given ragged array:
[39, 27, 1, 42, 35, 3],
[14, 93, 91, 90],
[5, 56, 10, 98, 2],
[105, 7, 5, 17]
the sum would be
row1: 77
row2: 105
row3: 154
row4: 112
so, the method would return an 2d array with the following order:
{{39,27,1,42,35,3},
{14,93,91,90},
{105,7,5,17},
{5,56,10,98,2}} 
```