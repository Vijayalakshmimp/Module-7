# # 🔁 Recursion:Sum of 1st N Natural numbers using Recursion in Python

## 🎯 AIM:
To write a Python program to find the sum of first n Natural Numbers.

## 🧠 ALGORITHM:

1. Start
2. Define a recursive function sum_natural(n) that:
  - Returns 0 if n <= 0 (Base Case).
  - Else, returns n + sum_natural(n - 1) (Recursive Case).
3. Take an integer input n from the user.
4. Call the function sum_natural(n) and store the result.
5. Print the result.
6. Stop

## 💻 PROGRAM:
~~~
def sum_of_numbers(n):
if(n<=0):
    return 0
return((n)+sum_of_numbers(n-1))
n = int(input())
print('Result is',sum_of_numbers(n))
~~~

## OUTPUT
<img width="694" height="296" alt="image" src="https://github.com/user-attachments/assets/8b483525-c863-4552-a621-f54a35f16146" />

## RESULT
Thus, the program has been executed and verified successfully.
