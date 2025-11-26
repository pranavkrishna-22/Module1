# Conditional Statements in Python: Even or Odd Checker

##  Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

##  Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

##  Program
```
num=int(input())
if num%2==0:
   print("EVEN")
else:
   print("ODD")
```
## Output
<img width="1051" height="225" alt="image" src="https://github.com/user-attachments/assets/e36d5882-90bf-43c1-ba59-08d20912f53c" />

## Result
Therefore, the program correctly identifies the parity (even or odd) of any integer entered by the user.
