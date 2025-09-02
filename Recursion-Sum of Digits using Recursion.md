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
def sum_of_numbers(n):
    
    if(n<=0):
    
        return 0

    return((n)+sum_of_numbers(n-1))

n = int(input())

print('Result is',sum_of_numbers(n))
## OUTPUT
<img width="522" height="240" alt="image" src="https://github.com/user-attachments/assets/e586c49f-75ba-496f-a274-87e882d66d82" />

## RESULT
Thus the Python program to find the sum of first n Natural Numbers is executed and verified successfully.
