# 🧪 Experiment – 7  
## Study of While Loop and For Loop in Python  

**Name:** Dev Anand  
**PRN:** 25070123039  
**Batch:** A2  

---

# 1️⃣ AIM

To study and implement iterative control structures in Python including:

- While loop  
- For loop  
- Break statement  
- Continue statement  
- Nested loops  
- Applications such as Factorial, Fibonacci Series, Palindrome, Armstrong Number, Prime Numbers, Matrix Multiplication and Pattern Programs  

---

# 2️⃣ OBJECTIVE

- To understand the concept of iteration in programming.
- To learn how repetitive tasks are handled efficiently.
- To differentiate between while loop and for loop.
- To apply loops in solving mathematical and logical problems.
- To understand nested loops and multidimensional data structures.

---

# 3️⃣ INTRODUCTION TO LOOPS

In programming, many problems require repetition of instructions. Writing repetitive statements manually makes programs lengthy and inefficient.  

Loops provide a structured way to execute a block of code multiple times until a specific condition is satisfied.

Loops improve:

- Code efficiency  
- Code readability  
- Logical thinking  
- Problem-solving ability  

Python provides two main types of loops:

1. While Loop  
2. For Loop  

---

# 4️⃣ WHILE LOOP

## Definition

A while loop repeatedly executes a block of code as long as a specified condition is True.

It is called an entry-controlled loop because the condition is checked before execution of the loop body.

## Working Mechanism

1. The condition is evaluated.
2. If the condition is True → loop body executes.
3. After execution, the condition is checked again.
4. If the condition becomes False → loop terminates.

## Characteristics

- Used when number of iterations is not known in advance.
- Suitable for condition-based repetition.
- Requires manual initialization and update.
- May lead to infinite loop if condition never becomes False.

---

# 5️⃣ FOR LOOP

## Definition

A for loop is used to iterate over a sequence such as range, list, string, or tuple.

It is generally used when the number of iterations is known beforehand.

## Range Function

range(start, stop, step)

- start → initial value (default 0)
- stop → ending value (exclusive)
- step → increment/decrement (default 1)

Example:
range(1, 6) generates 1, 2, 3, 4, 5.

## Characteristics

- Cleaner and more compact.
- Automatically handles increment.
- Lower risk of infinite loops.
- Suitable for sequence traversal.

---

# 6️⃣ BREAK STATEMENT

The break statement immediately terminates the loop even if the condition is True.

Used in:
- Searching operations
- Early termination conditions
- Exit control logic

When break executes, control transfers outside the loop.

---

# 7️⃣ CONTINUE STATEMENT

The continue statement skips the remaining statements of the current iteration and moves to the next iteration.

Used when:
- Certain values must be ignored.
- Filtering logic is required.

Difference:
- break → exits loop completely.
- continue → skips only one iteration.

---

# 8️⃣ NESTED LOOPS

A loop inside another loop is called a nested loop.

Used in:
- Matrix operations
- Pattern printing
- Multi-dimensional data structures
- Table generation

Nested loops increase time complexity depending on levels of nesting.

---

# 9️⃣ FACTORIAL USING LOOP

## Mathematical Definition

n! = n × (n-1) × (n-2) × ... × 1  

Defined only for non-negative integers.

Example:
5! = 120

## Logic Used

- Initialize factorial variable to 1.
- Multiply decreasing values of n.
- Stop when n becomes 0.

Time Complexity: O(n)

---

# 🔟 FIBONACCI SERIES

## Mathematical Definition

F₀ = 0  
F₁ = 1  
Fₙ = Fₙ₋₁ + Fₙ₋₂  

Series:
0 1 1 2 3 5 8 13 ...

Used in:
- Algorithm design
- Dynamic programming
- Mathematical modeling

Time Complexity: O(n)

---

# 1️⃣1️⃣ PALINDROME

A palindrome is a number or string that reads the same forward and backward.

Examples:
121  
madam  
racecar  

Logic:
- Reverse the number or string.
- Compare with original value.

---

# 1️⃣2️⃣ ARMSTRONG NUMBER

A number is an Armstrong number if:

Sum of each digit raised to the power of total number of digits equals the original number.

Example:
153

1³ + 5³ + 3³ = 153

Also known as a Narcissistic number.

---

# 1️⃣3️⃣ PRIME NUMBERS

A prime number is a number greater than 1 that has only two divisors: 1 and itself.

Logic:
- Check divisibility from 2 to n-1.
- If divisible → not prime.
- If no divisor found → prime.

Basic Time Complexity: O(n²)

---

# 1️⃣4️⃣ MATRICES IN PYTHON

A matrix is a two-dimensional data structure represented using a list of lists.

Example structure:
Row and column indexing is used to access elements.

## Matrix Multiplication Theory

If A is of order (m × n)  
and B is of order (n × p)

Then result matrix C will be of order (m × p)

Formula:

C[i][j] = Σ A[i][k] × B[k][j]

Requires three nested loops:
- i → rows
- j → columns
- k → multiplication index

Time Complexity: O(n³)

Applications:
- Computer graphics
- Machine learning
- Engineering simulations
- Physics calculations

---

# 1️⃣5️⃣ PATTERN PROGRAMS

Pattern programs use nested loops and spacing logic to generate visual shapes.

Concepts involved:

- Loop control
- String multiplication
- Indentation logic
- Space management

Common patterns:
- Pyramid
- Inverted pyramid
- Right angle triangle
- Number patterns

---

# 1️⃣6️⃣ DIFFERENCE BETWEEN WHILE AND FOR LOOP

| Feature | While Loop | For Loop |
|----------|------------|----------|
| Iteration Control | Condition-based | Sequence-based |
| Known Iterations | Not required | Required |
| Risk of Infinite Loop | Higher | Lower |
| Syntax Simplicity | Moderate | Simple |
| Best Used For | Conditional repetition | Fixed repetition |

---

# 1️⃣7️⃣ TIME COMPLEXITY ANALYSIS

- Single loop → O(n)
- Two nested loops → O(n²)
- Matrix multiplication → O(n³)
- Basic prime checking → O(n²)

Understanding time complexity is essential for writing efficient programs.

---

# 1️⃣8️⃣ CONCLUSION

This experiment successfully demonstrates:

- Iterative control structures in Python
- Mathematical computations using loops
- Logical problem solving
- Nested loop applications
- Matrix operations
- Pattern generation

The experiment builds strong foundational programming skills and prepares students for advanced topics like Data Structures and Algorithms.
✍ Author
Dev Anand B.Tech ENTC – Symbiosis Institute of Technology, Pune
