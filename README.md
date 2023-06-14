# Matrix-Calculator
Introduction
The aim of this homework is to practice on the use of vectors, loops and if-else statements. The use of vectors and loops are necessary in this problem.
Description
In this project, you will write a C++ program that will provide operations performed by a matrix calculator. There are four different operations that are provided by the calculator. The first operation is the addition of two matrices. The second operation is the multiplication of two matrices. The third operation is taking the power of a single matrix. The final operation is obtaining the transpose of a single matrix.

Input Checks and Program Flow
Firstly, your program will display a menu of operations for the user to choose from. The menu provided will look like this:
Pick a choice from the list:
1- Addition Operation
2- Multiplication Operation
3- Power Operation
4- Transpose Operation
5- Exit
The user should enter a choice from the menu provided. You may assume that the user will enter an integer between the correct range. You do not need to perform any checks on the input entered by the user when choosing an option from the menu.
***Your program should keep providing the menu until the user chooses the Exit option***
If the user picks the addition operation, the user will be asked to enter the dimensions of the first and second matrices respectively. If the two matrices are compatible for addition, the user will be asked to enter the numbers for the first matrix (row by row) and then display it. The user will then be asked to enter the numbers for the second matrix (row by row) and then display it. Once both matrices are entered, your program should calculate their sum and display the result .
If the user picks the multiplication operation, the user will be asked to enter the dimensions of the first and second matrices respectively. If the two matrices are compatible for multiplication, the user will be asked to enter the numbers for the first matrix (row by row) and then display it. The user will then be asked to enter the numbers for the second matrix (row by row) and then display it. Once both matrices are entered, your program should calculate their multiplication and display the result.
If the user picks the power operation, the user will be asked to enter the dimensions of a single matrix. If the matrix is compatible for the power operation, the user will be asked to enter the numbers for the single matrix (row by row). The user will then be asked to enter the power that the matrix will be raised to. Once the matrix and the power are entered, your program should perform the calculation and display the result.
***Note that the power (exponent) n given by the user MUST an INTEGER greater than or equal to 1 (n >= 1)***
If the user picks the transpose operation, the user will be asked to enter the dimensions of a single matrix. The user will then be asked to enter the numbers for the single matrix (row by row). Once the matrix is entered, your program should calculate the transpose matrix and then display it.
When the user is required to enter the dimensions of a matrix, the user is expected to enter two integers. The first integer represents the number of rows of the matrix and the second integer represents the number of columns of the matrix.
***IMPORTANT NOTE: ALL numbers entered to fill the matrices SHOULD be integers***

Operations
1- Addition
To add two matrices, just add the corresponding entries, and place this sum in the corresponding position in the matrix which results.
The following is an example of the addition operation:
The matrices have the same dimensions (2 x 2) so we can add them.
2- Multiplication
To check if the matrices are compatible for multiplication, the number of columns in the first matrix must be equal to the number of rows in the second matrix.
For example, Matrix A (3 x 2) and Matrix B (2 x 3) are compatible for multiplication.
For example, Matrix A (3 x 3) and Matrix B (2 x 3) are not compatible for multiplication.
If the matrices are compatible for multiplication then the resulting matrix will have the same number of rows as the first matrix and the same number of columns as the second matrix.
For example, Matrix A (3 x 2) and Matrix B (2 x 4) , the resulting multiplication will yield a matrix with the following dimensions (3 x 4).
To perform the multiplication, you take each row of the first matrix and multiply each column of the second matrix going by each element.
      
3- Power
To check if the matrix is compatible for the power operation, The number of rows should be equal to the number of columns for that matrix.
For example, Matrix A (2 x 2) is compatible for the power operation.
For example, Matrix B (3 x 2) is not compatible for the power operation.
If n is the exponent, to find the power of a matrix , multiply the matrix by itself n -1 many times. For example, if the exponent is 2 and we have a matrix:
4- Transpose
The transpose of a matrix is found by interchanging its rows into columns or columns into rows.
(2 x 3) (3 x 2)
The resulting transpose matrix will have the same number of columns as rows and the same number of rows as columns.
For example, Matrix A (3 x 1) has a Transpose Matrix 𝐴𝑇 (1 x 3) For example, Matrix B (4 x 2) has a Transpose Matrix 𝐵𝑇 (2 x 4)


