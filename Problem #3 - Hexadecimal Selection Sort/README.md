# Problem #3: Hexadecimal Selection Sort

Write a program that reads in a list of ten integers, written in hexadecimal, base 16, from the
keyboard and store them in an array. You may assume that each of these numbers contains no
more than three hexadecimal digits and that the alphabetic letters a-f will always appear in lower
case.

These integers should be sorted using a selection sort, which segments the array into a sorted
section and unsorted section. Initially the whole array is unsorted. The unsorted section is
repeatedly searched for the smallest value in the unsorted section. Once found, that smallest
value is swapped with the position in the array after the last sorted value, increasing the number
of sorted elements by one and decreasing the unsorted section by one. The process is repeated
until no elements remain in the unsorted section.

After each additional element is added to the sorted section the contents of the entire array
should be displayed on a separate line.

The following is a sample run of this program:
```
Enter ten hexadecimal integers: 7d 1df c99 45 f3 a 1b cc 10 23

00a 1df c99 045 0f3 07d 01b 0cc 010 023
00a 010 c99 045 0f3 07d 01b 0cc 1df 023
00a 010 01b 045 0f3 07d c99 0cc 1df 023
00a 010 01b 023 0f3 07d c99 0cc 1df 045
00a 010 01b 023 045 07d c99 0cc 1df 0f3
00a 010 01b 023 045 07d c99 0cc 1df 0f3
00a 010 01b 023 045 07d 0cc c99 1df 0f3
00a 010 01b 023 045 07d 0cc 0f3 1df c99
00a 010 01b 023 045 07d 0cc 0f3 1df c99
```