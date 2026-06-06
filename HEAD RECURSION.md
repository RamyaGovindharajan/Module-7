# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```
def fun(n):
    if n > 0:
        fun(n - 1)   # head recursion call
        print(n, end=" ")


n = int(input())

# If input is odd, convert to next even number
if n % 2 != 0:
    n += 1

fun(n)
```

## OUTPUT

<img width="487" height="222" alt="image" src="https://github.com/user-attachments/assets/7179b5f0-0075-4075-8a32-bf218de1d3a9" />


## RESULT

This program is excuted successfully and the output id verified
