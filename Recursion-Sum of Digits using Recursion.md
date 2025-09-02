# # 🔁 Recursion:Sum of first N Natural numbers using Recursion in Python

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
def sum_of_numbers(n):

    if(n<=0):
    
        return 0

    return((n)+sum_of_numbers(n-1))

n = int(input())

print('Result is',sum_of_numbers(n))

## OUTPUT
<img width="569" height="245" alt="Screenshot 2025-09-02 170438" src="https://github.com/user-attachments/assets/001fa157-580a-46a5-ac0a-f6a8f4da6b60" />

## RESULT
