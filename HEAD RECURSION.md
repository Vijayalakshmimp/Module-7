# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To Write a Python program to print odd numbers till ‘N’ using head recursion.

## 🧠 ALGORITHM:

1. Start
2. Define a recursive function odd(n) that:
   -Checks the base condition: if n == 0, return (stop recursion).
   -Make a recursive call to odd(n-1) first (ensuring head recursion).
   -After returning from recursion, check if n is odd (n % 2 != 0).
   -If true, print n.
3. Take an integer input N from the user.
4. Call the function odd(N).
5. Stop

## 💻 PROGRAM:
def odd(n):

    if n==0:

        return
        
    odd(n-1)
    
    if n%2!=0:
    
        print(n,end=' ')
        
n=int(input())

odd(n)
## OUTPUT
<img width="862" height="268" alt="image" src="https://github.com/user-attachments/assets/16b1665d-4cba-4580-8c6e-af0abf866c1c" />

## RESULT
Thus the Python program to print odd numbers till ‘N’ using head recursion is executed and verified successfully.
