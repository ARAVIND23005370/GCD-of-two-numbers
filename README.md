# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
``` PYTHON
Program to find the gcd of two number using function.
Developed by:ARAVIND
RegisterNumber:23005370  
def gcd():
    a=int(input())
    b=int(input())
    for i in range(1,min(a,b)):
        if a%i==0 and b%i==0:
            gcd1=i
    print("GCD of two numbers is:",gcd1)

```

## Output:
![Screenshot 2023-12-21 134817](https://github.com/ARAVIND23005370/GCD-of-two-numbers/assets/148514836/20a58d36-d4f2-41a4-922c-d1c13b1463d9)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
