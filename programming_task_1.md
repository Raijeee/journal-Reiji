# Ask the user for  2 numbers, A and B, Output TRUE if one of them is 10 or if their sum is 10

```.py
#Get user input
a=int(input("What is your first number? > "))
b=int(input("What is your second number? > "))
#See if either both variables are equal to 10 or the sum of both is equal to 10
if a==10 or b==10 or a+b==10:
#If true print true
    print("TRUE")
else:
#otherwise print false
    print("FALSE")
```
