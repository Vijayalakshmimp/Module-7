# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To Write a Python program to find the sum of first n Natural Numbers.

## 🧠 ALGORITHM:
1. Start
2. Define a recursive function sum_natural(n) that:
   -Returns 0 if n <= 0 (Base Case).
   -Else, returns n + sum_natural(n - 1) (Recursive Case).
3. Take an integer input n from the user.
4. Call the function sum_natural(n) and store the result.
5. Print the result.
6. Stop

## 💻 PROGRAM:
def sum_natural(n):

    if n <= 0:

        return 0
    
    return n + sum_natural(n - 1)

n = int(input())

print("Result is", sum_natural(n))

## OUTPUT
<img width="569" height="245" alt="image" src="https://github.com/user-attachments/assets/20d042cc-49f6-4ebb-81bc-d1579b99e59e" />

## RESULT
Thus the Python program to find the sum of first n Natural Numbers is executed and vrified successfully.
