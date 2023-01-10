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
Developed by: Marella Dharanesh
RegisterNumber:  22000785
def n_m(num,num_iters=100):
    a=float(num)
    for i in range(num_iters):
        num=0.5*(num+a/num)
    return num
a=int(input())
print("Square root of the number:",n_m(a))
```

## Output:

![Screenshot (18)](https://user-images.githubusercontent.com/118707669/211528855-8a5f7672-8f61-488a-a3e1-d2fa967c4f61.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
