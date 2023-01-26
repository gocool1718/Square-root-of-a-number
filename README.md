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
Developed by: GOKUL S
RegisterNumber:  22008488
*/
```
a=int(input())

def sq(x,it=100):

    a=float(x)
    
    for i in range(it):
    
        x=0.5*(x+(a/x))
        
    return x
    
print('Square root of the number:',sq(a))
``

## Output:
![gcd of two number](gcd.png)

![Screenshot (4)](https://user-images.githubusercontent.com/121148715/214847944-ad025924-4a2c-4abb-87c2-34e5bd5d89de.png)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
