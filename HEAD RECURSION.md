# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(num)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
~~~
def fun(num):
    if num < 0 or int(num) != num:
        return 0
    elif num == 0:
        return 0
    else:
        return (num % 10) + fun(num//10)
num= int(input())
print(fun(num))
~~~

## OUTPUT
<img width="467" height="220" alt="image" src="https://github.com/user-attachments/assets/d3155e14-cad0-4536-a359-4781912ed199" />


## RESULT
Thus the required ouput is Verified.
