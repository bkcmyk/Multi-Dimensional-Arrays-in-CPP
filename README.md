# Multi-Dimensional-Arrays-in-CPP
## Aim
To study and implement **Multidimensional Arrays – Matrices in C++** by building simple programs that:
- Take matrix input from user and display it  
- Addition of two matrix  
- Multiplication  
- Diagonal Addition  
- Transpose  
- Compare elements of first row to the second row

## Tools Used
VS Code, or an online compiler such as Programiz, Replit, or OnlineGDB.

## Theory (Multidimensional Array)
A **2D array** stores values in a grid of rows and columns (like a matrix).  
Typical operations include reading values, displaying them, adding/multiplying matrices, computing diagonal sums, transposing (swapping rows and columns), and comparing rows.

## Tasks Covered
- 2-D Array input from user  
- Display matrix  
- Addition of two matrices  
- Multiplication of matrices  
- Diagonal addition (main diagonal sum)  
- Transpose of a matrix  
- Compare first row with second row  

## Input Size & Limits
- Programs ask the **size from the user** at runtime.
- Implementations use fixed arrays (e.g., `int A[100][100];`).  
  Keep `rows, cols ≤ 100` to stay within bounds.

---

## Algorithms

________________________________________
**1) Enter and Show a Matrix**  
**Goal:** Ask the user to enter numbers for a matrix and then show the matrix exactly as it looks.  
**Steps:**
1.	Ask the user: "How many rows does your matrix have?" → store as rows.  
2.	Ask the user: "How many columns does your matrix have?" → store as columns.  
3.	Tell the user: "Now enter the numbers row by row:".  
4.	Fill the matrix by reading numbers one by one until all boxes are filled.  
5.	Show the complete matrix by printing each row on a new line.  
________________________________________
**2) Add Two Matrices**  
**Goal:** Add each position of two matrices and show the result.  
**Steps:**
1.	Ask: "How many rows and columns will your matrices have?" → store as rows and columns.  
2.	Ask: "Enter the first matrix:" → fill it row by row.  
3.	Ask: "Enter the second matrix:" → fill it row by row.  
4.	For each position in the grid, add the two numbers from the same position (one from the first matrix, one from the second).  
5.	Store each sum in a new matrix.  
6.	Show the new matrix as the result.  
________________________________________
**3) Multiply Two Matrices**  
**Goal:** Multiply two matrices using the standard multiplication method.  
**Steps:**
1.	Ask for the size of the first matrix: "Enter number of rows and columns of the first matrix:".  
2.	Ask for the size of the second matrix: "Enter number of rows and columns of the second matrix:".  
3.	If the number of columns in the first matrix is not the same as the number of rows in the second matrix, show:  
"Sorry, these matrices cannot be multiplied" and stop.  
4.	Ask the user to enter the first matrix (row by row).  
5.	Ask the user to enter the second matrix (row by row).  
6.	To find the number in position (row i, column j) of the result:  
o	Multiply each number in row i of the first matrix by the matching number in column j of the second matrix.  
o	Add all those products together.  
7.	Repeat step 6 for every position to fill the result matrix.  
8.	Show the result matrix.  
________________________________________
**4) Find the Sum of the Main Diagonal**  
**Goal:** Add the numbers that lie from the top-left to bottom-right corner of a square matrix.  
**Steps:**
1.	Ask: "What size is your square matrix?" (one number for both rows and columns).  
2.	Ask the user to enter the matrix numbers (row by row).  
3.	Start a total sum at 0.  
4.	For each row i, pick the number in column i (this is the diagonal). Add it to the sum.  
5.	Show the final sum.  
________________________________________
**5) Find the Transpose of a Matrix**  
**Goal:** Flip the matrix over its diagonal so rows become columns.  
**Steps:**
1.	Ask the user for the number of rows and columns.  
2.	Enter the matrix numbers row by row.  
3.	To make the transpose:  
o	Take the first column of the original matrix and make it the first row of the new matrix.  
o	Repeat for every column.  
4.	Show the new matrix.  
________________________________________
**6) Compare First and Second Row**  
**Goal:** Check if the first row is exactly the same as the second row.  
**Steps:**
1.	Ask the user for the number of rows and columns.  
2.	If the matrix has fewer than 2 rows, show: "You need at least 2 rows to compare" and stop.  
3.	Enter the matrix numbers row by row.  
4.	Compare each number in the first row with the number in the same position in the second row.  
5.	If all numbers match, say: "The first row is the same as the second row".  
6.	If any number is different, say: "The first row is not the same as the second row".  
________________________________________

---

## Outcome
By completing this exercise, you will:
- Correctly **read** matrix sizes and elements from the user.
- **Display** matrices in a clear, row-by-row format.
- Perform **matrix addition**, **matrix multiplication**, **transpose**, and **main diagonal sum**.
- **Validate preconditions** (e.g., multiplication requires first matrix columns = second matrix rows; diagonal sum requires a square matrix).
- **Compare rows** to determine equality element-by-element.
- Gain confidence using **nested loops** and **2D array indexing** in C++.


