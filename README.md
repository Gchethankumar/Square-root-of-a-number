# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: G.Chethan kumar.
RegisterNumber:  212222240022.

def sqrt():
    num1=int(input())
    num2=float(num1)
    for i in range(100):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)
sqrt()
```

## Output:

![Screenshot 2023-04-27 061045](https://user-images.githubusercontent.com/118348224/234731485-96dc40e1-f298-4d14-8f0b-290e9f85ce4f.png)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
