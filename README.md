# study_of_loops
learning loops in python
🧪 Experiment – 7
Study of While Loop and For Loop in Python
Name: Dev Anand
PRN: 25070123039
Batch: A2
1️⃣ AIM

To study and implement iterative control structures in Python including:

While loop

For loop

Break statement

Continue statement

Nested loops

Applications of loops such as:

Factorial

Fibonacci Series

Palindrome

Armstrong Number

Prime Numbers

Matrix Multiplication

Pattern Programs

2️⃣ OBJECTIVE

To understand iteration in programming.

To learn how repetitive tasks are handled efficiently.

To differentiate between while loop and for loop.

To apply loops in mathematical and logical problems.

To understand nested loops and multidimensional data handling.

3️⃣ INTRODUCTION TO LOOPS

In programming, many problems require repetition of instructions. Instead of writing the same statement multiple times, loops are used to execute a block of code repeatedly until a condition is satisfied.

Loops improve:

Code efficiency

Code readability

Logical thinking

Problem-solving ability

Python provides two main types of loops:

While Loop

For Loop

4️⃣ WHILE LOOP
Definition

A while loop repeatedly executes a block of code as long as a specified condition is True.

It is called an entry-controlled loop because the condition is checked before execution of the loop body.

Syntax
while condition:
    statement(s)
Working Mechanism

Condition is evaluated.

If True → execute loop body.

After execution → condition checked again.

If False → loop terminates.

Characteristics of While Loop

Used when number of iterations is not known in advance.

Suitable for condition-based repetition.

Risk of infinite loop if condition never becomes False.

Requires manual initialization and increment/decrement.

Example Applications
✔ Printing numbers from 1 to N
✔ Factorial calculation
✔ Fibonacci series
✔ Reverse a number
✔ Palindrome check
5️⃣ FOR LOOP
Definition

A for loop is used to iterate over a sequence (range, list, string, tuple, etc.).

It is preferred when the number of iterations is known beforehand.

Syntax
for variable in range(start, stop, step):
    statement(s)
Range Function

range(start, stop, step)

start → initial value (default 0)

stop → ending value (exclusive)

step → increment/decrement value (default 1)

Example:

range(1,6)

Generates:
1, 2, 3, 4, 5

Characteristics of For Loop

Used when number of iterations is fixed.

Cleaner and more compact than while loop.

Automatically handles increment.

Reduces chances of infinite loops.

6️⃣ BREAK STATEMENT
Definition

The break statement immediately terminates the loop even if the condition is True.

Used in:

Searching operations

Exit conditions

Early termination logic

Working:
When break executes → control goes outside the loop.

7️⃣ CONTINUE STATEMENT
Definition

The continue statement skips the remaining statements in the current iteration and moves to the next iteration.

Used when:

Certain values need to be ignored.

Filtering logic is required.

Difference from break:

break → exits loop completely.

continue → skips only one iteration.

8️⃣ NESTED LOOPS
Definition

A loop inside another loop is called a nested loop.

Structure:

for i in range():
    for j in range():
        statements

Applications:

Matrix operations

Pattern printing

Multiplication tables

Multi-dimensional arrays

9️⃣ FACTORIAL USING LOOP
Mathematical Definition

n! = n × (n-1) × (n-2) × ... × 1

Factorial is defined only for non-negative integers.

Example:
5! = 120

Logic:

Initialize fact = 1

Multiply decreasing values

Stop when number becomes 0

Time Complexity: O(n)

🔟 FIBONACCI SERIES
Mathematical Definition

Fibonacci sequence is defined as:

F₀ = 0
F₁ = 1
Fₙ = Fₙ₋₁ + Fₙ₋₂

Series:
0 1 1 2 3 5 8 13 ...

Used in:

Computer algorithms

Dynamic programming

Mathematical modeling

Time Complexity: O(n)

1️⃣1️⃣ PALINDROME

A palindrome is a number or string that reads the same forward and backward.

Examples:
121
madam
racecar

Logic:

Reverse the number/string

Compare with original value

1️⃣2️⃣ ARMSTRONG NUMBER

Definition:

A number is an Armstrong number if:

Sum of (each digit raised to power of number of digits) = original number

Example:
153

1³ + 5³ + 3³ = 153

Also known as Narcissistic number.

1️⃣3️⃣ PRIME NUMBERS

Definition:

A prime number is a number greater than 1 that has only two divisors:
1 and itself.

Logic Used:

Check divisibility from 2 to n-1.

If divisible → not prime.

If no divisor found → prime.

Time Complexity (basic method): O(n²)

1️⃣4️⃣ MATRICES IN PYTHON
Definition

A matrix is a two-dimensional data structure represented using lists of lists.

Example:

A = [[1,2,3],
     [4,5,6],
     [7,8,9]]

Access:
A[row][column]

Matrix Multiplication Theory

If A is of order (m × n)
and B is of order (n × p)

Then result matrix C will be of order (m × p)

Formula:

C[i][j] = Σ A[i][k] × B[k][j]

This requires 3 nested loops:

i → rows

j → columns

k → multiplication index

Time Complexity: O(n³)

Applications:

Computer graphics

Machine learning

Physics simulations

Engineering calculations

1️⃣5️⃣ PATTERN PROGRAMS

Pattern programs use nested loops to create visual shapes.

Concepts involved:

Loop control

String multiplication

Indentation logic

Space management

Examples:

Pyramid

Inverted pyramid

Right angle triangle

Number patterns

1️⃣6️⃣ DIFFERENCE BETWEEN WHILE AND FOR LOOP
Feature	While Loop	For Loop
Condition Based	Yes	Yes
Known Iterations	No	Yes
Risk of Infinite Loop	High	Low
Syntax Simplicity	Moderate	Simple
Used In	Condition problems	Sequence problems
1️⃣7️⃣ TIME COMPLEXITY ANALYSIS

Simple loop → O(n)

Nested loop (2 levels) → O(n²)

Matrix multiplication → O(n³)

Prime check (basic) → O(n²)

Understanding time complexity helps in writing efficient programs.

1️⃣8️⃣ CONCLUSION

Through this experiment, the following concepts were successfully studied and implemented:

Iterative control structures

Conditional loop termination

Logical problem solving

Mathematical computations using loops

Nested loop applications

Matrix operations

Pattern generation

This experiment strengthens foundational programming logic and prepares for advanced topics such as data structures and algorithms.
