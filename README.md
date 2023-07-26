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
#GCD of a Number by using fuction.
#Developed by:AARON I
#Register Number:23002289
```
def gcd():
   n1=int(input())
   n2=int(input())
   if n1>n2:
      small=n2
   else:
      small=n1
   for i in range(small,0,-1):
      if n1%i==0 and n2%i==0:
         gcd=i
         break
   print("GCD of two numbers is:",gcd)
```

## Output:
![output](/Screenshot%202023-07-26%20132137.png)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
