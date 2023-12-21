# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Get the input from the user.
2. Assign n/2 to b.
3. Perform 1000 iterations using loop.
4. Calculate  b = 0.5 * (b + n / b) for 1000 iterations.
5. Return number (n).
## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: Thaksha Rishi
RegisterNumber: 23013212  
n=int(input())
b=n/2
for i in range(1000):
    b=0.5*(b+n/b)
print("Square root of the number:",b)
```
## Output:
![Alt text](<Screenshot 2023-12-21 170105.png>)
![Alt text](<Screenshot 2023-12-21 165020.png>)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
