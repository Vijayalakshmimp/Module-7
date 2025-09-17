# 📐 Taylor Series:sinh(x) Evaluation using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate the value of **sinh(x)** for **n terms** using recursion.

---

## 🧠 ALGORITHM:

1. **Start**
2. Read input for variable `x` (angle or number)
3. Read input for variable `n` (number of terms)
4. Define a function `fact(n)`:
   - If `n <= 1`, return 1
   - Else, return `n * fact(n - 1)` (recursive factorial)
5. Define a function `sinh(x, n)`:
   - If `n == 0`, return `x`
   - Else, return `(pow(x, 2*n + 1) / fact(2*n + 1)) + sinh(x, n - 1)`
6. Call the `sinh(x, n)` function and print the result
7. **Stop**

---

## 💻 PROGRAM:
~~~
def f(x,y):
if y==0:
    return x
else:
    return (x**(2*y+1))/fact(2*y+1)+f(x,y-1)
def fact(y):
if y==0:
    return 1
else:
    return y*fact(y-1)
a=int(input())
b=int(input())
print(f(a,b))
~~~

## OUTPUT
<img width="771" height="305" alt="image" src="https://github.com/user-attachments/assets/50807025-b48b-46f2-803d-86ee024b6bbc" />

## RESULT
Thus, the program has been executed and verified successfully.
