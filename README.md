# exp8

# Aim

The objective of this experiment is to understand and implement the for loop in Python through multiple examples. The programs demonstrate iteration, accumulation, nested loops, matrix operations, prime number logic, and pattern generation.

# Introduction

Loops are fundamental in programming as they allow repeated execution of a block of code. The for loop in Python is used for iterating over sequences such as ranges, lists, strings, or other iterable objects.


# Programs & Algorithms
1] Program 1 – Print Numbers Using for Loop

Description:
Prints numbers from 1 to 5 using the range() function.

Algorithm:

Use range(1, 6) to generate numbers from 1 to 5.

Iterate through the range using a for loop.

Print each value of i.

Concepts Used:
for loop, range() function

2] Program 2 – Sum of First N Natural Numbers

Description:
Calculates the sum of first N natural numbers entered by the user.

Algorithm:

Accept integer input n from the user.

Initialize a variable total = 0.

Iterate from 1 to n using range(1, n+1).

Add each value to total.

Print the final sum.

Concepts Used:
User input, accumulation, loop iteration

3] Program 3 – Display a 3×3 Matrix

Description:
Displays elements of a predefined 3×3 matrix.

Algorithm:

Define matrix A using nested lists.

Use an outer loop for rows (i).

Use an inner loop for columns (j).

Print each matrix element with formatting.

Concepts Used:
Nested loops, list indexing

4] Program 4 – Multiplication of Two 3×3 Matrices

Description:
Multiplies two matrices using triple nested loops.

Algorithm:

Define matrices A and B.

Initialize result matrix with zeros.

Use three nested loops:

Outer loop → rows of A

Middle loop → columns of B

Inner loop → multiplication & summation

Store computed values in result matrix.

Print the result.

Concepts Used:
Matrix multiplication logic, triple nested loops

5] Program 5 – Print Prime Numbers (2 to 49)

Description:
Identifies and prints prime numbers in a given range.

Algorithm:

Iterate numbers from 2 to 49.

For each number, check divisibility from 2 to num-1.

If divisible → break loop (not prime).

If loop completes → number is prime.

Print prime numbers.

Concepts Used:
Loop control, break, else with loops

6] Program 6 – Reverse Star Pattern

Description:
Prints decreasing star pattern from 100 to 1.

Algorithm:

Iterate from 100 down to 1 using negative step.

Print "*" multiplied by loop variable.

Concepts Used:
Reverse iteration, string multiplication

7] Program 7 – Pyramid Star Pattern

Description:
Generates a pyramid shape using spaces and stars.

Algorithm:

Define number of rows.

Iterate from 1 to rows.

Print spaces for alignment.

Print stars proportional to row number.

# Conclusion

The experiment successfully demonstrated the versatility of the for loop in Python. Various practical implementations highlighted how loops simplify repetitive tasks, mathematical operations, and structured output generation.
