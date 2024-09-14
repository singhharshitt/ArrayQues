# ArrayQues
<br>
<b>Q1. Amy has created a class called MatrixManipulator that reads a matrix, swaps two specified columns, and prints the modified matrix. Implement a program using this class to perform the column swap and display the resulting matrix.</b>
<br>
<br>
Input format :<br>
The first line of input consists of an integer T, representing the number of test cases.<br>

For each test case:<br>

<i>The first line contains two integers R and C, representing the number of rows and columns in the matrix.
The next R lines each contain C space-separated integers, representing the matrix elements.
The last line contains two integers c1 and c2, representing the indices of the columns to be swapped (0-based).</i>
<br>
Output format :<br>
For each test case, print the matrix after swapping the specified columns.
<br>

Code constraints :<br>
The given test cases fall under the following constraints:<br>

1 ≤ T ≤ 10<br>

1 ≤ R, C ≤ 10<br>

0 ≤ matrix element ≤ 1000<br>
<br>
<br>
Sample test cases :<br>
Input 1 :<br>
2 <br>
3 3 <br>
1 2 3 <br>
4 5 6 <br>
7 8 9 <br>
0 2 <br>
2 2 <br>
1 2 <br>
3 4 <br>
1 0 <br>
<br>
Output 1 :<br>
3 2 1 <br>
6 5 4 <br>
9 8 7 <br>
2 1 <br>
4 3 <br>
<br>
Input 2 :<br>
1<br>
3 3 <br>
8 5 3 <br>
4 1 6 <br>
7 2 9 <br>
2 1 <br>
<br>
Output 2 :<br>
8 3 5 <br>
4 6 1 <br>
7 9 2 <br>
<br>
<br>
<b>Q2. Rina is managing the inventory for a library, where each row of a 2D matrix represents the number of different genres of books available on each shelf. To get a better overview, she wants to replace each number in a row with the sum of all numbers in that row. </b>
<br>
Write a program to help Rina transform the matrix accordingly.<br>
<br>

<b>Input format :</b><br>

The first line of input consists of an integer T, representing the number of test cases.
<br>

For each test case:<br>

The first line contains two integers R and C, representing the number of rows and columns.<br>
The next R lines each contain C space-separated integers, representing the count of books of a specific genre on a shelf.<br>

<b>Output format :</b>
<br>
For each test case, the output prints the transformed 2D matrix where each element in a row is replaced with the sum of the elements in that row.<br>
<br>

Sample test cases :<br>
Input 1 :<br>
2 <br>
3 4<br>
8 2 4 9<br>
4 5 6 1<br>
7 8 9 3<br>
2 5<br>
1 2 3 5 7<br>
3 4 8 9 6<br><br>
Output 1 :<br>
23 23 23 23 <br>
16 16 16 16 <br>
27 27 27 27 <br>
18 18 18 18 18 <br>
30 30 30 30 30 <br>
Input 2 :<br>
1<br>
3 3 <br>
48 65 83 <br>
45 21 76 <br>
71 32 98 <br>
Output 2 :<br>
196 196 196 <br>
142 142 142 <br>
201 201 201 <br>
