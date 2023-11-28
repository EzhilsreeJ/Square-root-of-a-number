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

## Input:
![gcd of two number](gcd.png)


## Program:
```py
def root(x,b):
    y=0.5*(x+b/x)
    if y==x:
        return y
    else:
        return root(y,b)
b=int(input())
res=root(b,b)
print("Square root of the number:",res)

```

## Output:
![Alt text](OUTPUT.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
