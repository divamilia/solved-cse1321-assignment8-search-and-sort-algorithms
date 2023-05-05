Download Link: https://assignmentchef.com/product/solved-cse1321-assignment8-search-and-sort-algorithms
<br>
Note: This assignment exercises build on the exercises you completed in Lab 14.

<strong><u>Program 1:</u></strong> Design (pseudocode) and implement (source code) a program (name it Occurrences) to determine whether two two-dimensional arrays are equivalent or not. Two arrays are equivalent if they contain the same values in any order. The program main method defines two two-dimensional array of size 3-by-3 of type integer, and prompts the user to enter integer values to initialize the arrays.




The main method calls method isEquivalent()that takes two two-dimensional arrays of integer and returns true (boolean value) if the arrays contain the same values in any order, otherwise it returns false.




Hint: use a sort method from Lab 14 in developing the solution for this problem.




Document your code and properly label the input prompts and the outputs as shown below.




<u>Sample run 1:</u>




Array A:

1   2   3

4   5   6

7   8   9




Array B:

1   2   3

6   5   4

7   8   9




Judgment: The arrays are equivalent.







<u>Sample run 2:</u>




Array A:

1   1   1

1   5   6

1   1   1




Array B:

1   1   1

1   6   6

1   1   1




Judgment: The arrays are not equivalent.













<strong><u>Program 2:</u></strong> Re-work program #5 (WeeklyHours) from the previous assignment such that




<ol>

 <li>The program prints out the day an employee worked most hours (utilize Binary search from Lab 14 to implement this fucntionality).</li>

</ol>




<ol>

 <li>The program outputs are displayed in ascending order (stored) by Weekly Hours. Notice that we modifying method addHours()to display the outputs sorted by total weekly hours for each employee as shown below.</li>

</ol>




<u>Sample run 1:</u>




Employees Data:

Mon  Tue  Wed  Thu  Fri  Sat  Sun

Employee1   5    3    2    9    6    5    7

Employee2   7    6    8    5    5    4    5

Employee3   1    2    2    1    5    8    7




Employee1 worked most hours on Thursday

Employee2 worked most hours on Wednesday

Employee3 worked most hours on Saturday




Employee#    Weekly Hours

—————————-

3            26

1            37

2            40







<u>Sample run 2:</u>




Employees Data:

Mon  Tue  Wed  Thu  Fri  Sat  Sun

Employee1   10   2    7    2    0    3    8

Employee2   5    6    1    5    1    4    2

Employee3   1    5    2    6    4    8    7




Employee1 worked most hours on Monday

Employee2 worked most hours on Tuesday

Employee3 worked most hours on Saturday




Employee#    Weekly Hours

—————————-

2            24

1            32

3            33


