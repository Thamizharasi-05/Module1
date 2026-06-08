# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
a=int(input())
if a%2==0:
    print(a,"is an Even number")
    if a<=30:
        print(a,"is lesser than or equal to 30")
    else:
        print(a,"is greater than 30")
else:
    print(a,"is NOT an Even number")
```
## Output

<img width="918" height="327" alt="image" src="https://github.com/user-attachments/assets/4e799a6a-3a06-4c8f-b298-065b4f64e500" />

## Result
Thus, Python program to check whether the given number is even or odd using if...else statements is successfull.
