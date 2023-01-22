# Find the square root of a number

## AIM:
To write a program to find the square root of a number.
## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Name:sirisha onteddu
ref.no:22003264
def sqrt():
    x=int(input())
    b=x
    for i in range(10):
        x=0.5*(x+b/x)
    return x
print("Square root of the number:",sqrt())
```

## Output:
![image](https://user-images.githubusercontent.com/119389139/213917595-8b516581-25f5-4e0b-9f39-3977549a2a81.png)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
