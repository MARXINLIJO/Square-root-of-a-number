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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: MARXIN LIJO.M
RegisterNumber:  23013468
n=int(input())
a=1e-6
m=100
g=n/2.0
for _ in range(m):
    new=0.5*(g+n/g)
    if(abs(new-g)<a):
        break
    g=new
print(f"Square root of the number: {new}")


*/
```

## Output:
![image](https://github.com/MARXINLIJO/Square-root-of-a-number/assets/145742540/227711e7-b6b0-443f-9a97-df6c15223f61)
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
