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
```
# Program to find the gcd of a given number using function
# Developed by: DILLIARASU M
# RegisterNumber: 212223230049
def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller = n2
    else:
        smaller = n1
    for i in range (1,smaller+1):
        if(n1%i==0 and n2%i==0):
           gcd1=i
    print("GCD of two numbers is:",gcd1)
```

## Output:
![Screenshot 2024-04-14 115336](https://github.com/Dilliarasu0105/GCD-of-two-numbers/assets/144979593/572b54a5-9c37-4077-a5f1-3d4d85adefa0)
![Screenshot 2024-04-14 115350](https://github.com/Dilliarasu0105/GCD-of-two-numbers/assets/144979593/6e3a68a2-bac1-4da0-8308-f110b8f4bc5b)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
