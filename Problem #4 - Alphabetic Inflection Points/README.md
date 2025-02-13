# Problem #4: Alphabetic Inflection Points

Write a program that reads in a string of lower case letters from the keyboard and determines the
alphabetical inflection points that include both peaks and valleys. A peak is the point where the
sequence of letters changes from alphabetic order to reverse alphabetic order. A valley is the
point where the sequence of letters changes from reverse alphabetic order to alphabetic order.

A check should be made first to ensure that no letter appears twice in a row and that all
characters are lower case letters. If either check fails, an error message should be displayed and
the program should terminate.

The output should contain each inflection point labeling it as either a peak or valley and
displaying the three letters associated with that point of inflection.

The following are three sample runs of this program:
```
Enter a string of lower case letters: abgjgekkgiop
Contains two of the same characters in a row

Enter a string of lower case letters: abcJndr5s
Contains characters that are not lower case letters

Enter a string of lower case letters: abdghfdcbgklprogbdjz
Peak: ghf
Valley: cbg
Peak: pro
Valley: gbd
```