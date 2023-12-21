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

### Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: DHANUSYA.K
Register no: 23006651
num=int(input())
a=1e-6
max=100
guess = num/2.0
for i in range(max):
    new = 0.5*(guess+num/guess)
    if abs(new-guess)<a:
        break
    guess=new
print(f"Square root of the number: {new}") 
*/
```

## Output:
![gcd of two number](gcd.png)
![Screenshot 2023-12-21 082757](https://github.com/Dhanu654/Square-root-of-a-number/assets/148514965/fe6cd738-f0e2-4503-b302-aa2da421e106)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
