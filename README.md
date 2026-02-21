# 🧪 Experiment – 7  
## Study of While Loop and For Loop in Python  

**Name:** Dev Anand  
**PRN:** 25070123039  
**Batch:** A2  

---

# 📌 Aim

To study and implement iterative control structures in Python including:

- While Loop  
- For Loop  
- Break Statement  
- Continue Statement  
- Nested Loops  
- Matrix Operations  
- Pattern Programs  
- Mathematical Applications  

---

# 📚 Introduction

Loops are used in programming to execute a block of code repeatedly.  
Instead of writing repetitive statements manually, loops help automate repetition.

Python provides two main types of loops:

1. **While Loop**
2. **For Loop**

---

# 🔁 While Loop

### Syntax

```python
while condition:
    statements
Example: Print Numbers from 1 to 5
i = 1
while i <= 5:
    print(i)
    i += 1
🔢 Factorial Using While Loop
n = int(input("Enter the number: "))
fact = 1

while n > 0:
    fact *= n
    n -= 1

print("Factorial:", fact)
🔢 Fibonacci Series
n = int(input("Enter number of terms: "))
a, b = 0, 1
i = 0

while i < n:
    print(a)
    a, b = b, a + b
    i += 1
🔄 Reverse a Number
num = int(input("Enter a number: "))
rev = 0

while num > 0:
    digit = num % 10
    rev = rev * 10 + digit
    num //= 10

print("Reversed Number:", rev)
🔍 Palindrome Check (Number)
n = int(input("Enter a number: "))
original = n
rev = 0

while n > 0:
    digit = n % 10
    rev = rev * 10 + digit
    n //= 10

if original == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
🔍 Palindrome Check (String)
s = "madam"
i, j = 0, len(s) - 1
is_palindrome = True

while i < j:
    if s[i] != s[j]:
        is_palindrome = False
        break
    i += 1
    j -= 1

if is_palindrome:
    print("Yes")
else:
    print("No")
🔴 Break Statement
for i in range(1, 10):
    if i == 3:
        break
    print(i)
🟡 Continue Statement
i = 1
while i <= 10:
    if i == 5:
        i += 1
        continue
    print(i)
    i += 1
🔁 For Loop
Syntax
for variable in range(start, stop, step):
    statements
Example: Print 1 to 5
for i in range(1, 6):
    print(i)
➕ Sum of First N Numbers
n = int(input("Enter a number: "))
total = 0

for i in range(1, n + 1):
    total += i

print("Sum:", total)
🔁 Nested Loop Example
for i in range(1, 4):
    for j in range(1, 4):
        print(i, j)
🧱 Matrix Multiplication (3×3)
A = [[1,2,3],
     [4,5,6],
     [1,2,1]]

B = [[1,1,1],
     [6,5,4],
     [3,2,1]]

Result = [[0,0,0],
          [0,0,0],
          [0,0,0]]

for i in range(3):
    for j in range(3):
        for k in range(3):
            Result[i][j] += A[i][k] * B[k][j]

print("Product of matrices:")
for row in Result:
    print(row)
🔢 Armstrong Number
num = int(input("Enter a number: "))
total = 0
length = len(str(num))

for digit in str(num):
    total += int(digit) ** length

if total == num:
    print("Armstrong")
else:
    print("Not Armstrong")
🔢 Prime Numbers (2 to 50)
for num in range(2, 50):
    for j in range(2, num):
        if num % j == 0:
            break
    else:
        print(num, end=" ")
⭐ Pattern Programs
Inverted Right Angle Triangle
for i in range(5, 0, -1):
    print("* " * i)
📊 Conclusion

This experiment demonstrates:

Loop structures in Python

Mathematical problem-solving

Nested loops

Matrix operations

Logical programming techniques

It builds strong foundational knowledge for Data Structures and Algorithms.
