# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

# step 1:
Define a function.
# step 2:
Get the two numbers from the user.
# step 3:
Compare the two values, to find the smaller number.
# step 4: 
Use for() and if() loop to find the GCD of the two numbers.
# step 5:
End program.

## Program:
```
# Program to find the gcd of two number using function.
# Developed by: Ganesh D
# RegisterNumber: 23013987 
def gcd():
    n1,n2=int(input()),int(input())
    if n1<n2:
        smaller=n1
    else:
        smaller=n2
    for i in range(1,smaller+1):
        if n1%i==0 and n2%i==0:
            gcd=i
    print("GCD of two numbers is:",gcd)  

```

## Output:
<img width="629" alt="GCD of two numbers" src="https://github.com/Ganesh23013987/GCD-of-two-numbers/assets/147473768/cd139239-5c9a-4577-8f64-6118b1c38355">


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
Then, the program code is successfully executed.
