## Minimum of two numbers

```.py
#Get input of two values (a,b)
a = int(input("What is your first value? > "))
b = int(input("What is your second value? > "))

#If b is bigger than a then print a, otherwise print b
if a < b:
    print (a)
else:
    print (b)
```
## Sign functions

```.py
# Identify users input
a=int(input("What is your number? > "))

# If input is bigger than 0 print 1
if a > 0:
    print("1")
    
# If input is equal to 0
elif a == 0:
    print("0")
    
# Otherwise print -1 (bcs its a negative number)
else:
    print("-1")
```
## Minimum of three numbers
```.py
a = int(input("What is your first value? > "))
b = int(input("What is your second value? > "))
c = int(input("What is your third value? > "))
if a<b and a<c:
    print (a)
if b<a and b<c:
    print(b)
if c<a and c<b:
    print (c)
```
## Equal Numbers
```.py
a = int(input())
b = int(input())
c = int(input())

if a == b and b == c:
    print ("3")
elif a == b:
    print ("2")
elif b==c:
    print("2")
elif a==c:
    print("2")
else:
    print("0")
```
## Rook move
```.py
a= int(input())
b= int(input())
c= int(input())
d= int(input())

if a==c or b==d:
    print("YES")
else:
    print("NO")
```
## Chess board - Same color 
```.py
a=int(input())
b=int(input())
c=int(input())
d=int(input())

if ((a+b+c+d)%2) == 0:
    print("YES")
else:
    print("NO")
```
## King move
```.py
a=int(input())
b=int(input())
c=int(input())
d=int(input())
if -1<=(a-c)<=1 and -1<=(b-d)<=1:
    print("YES")
else:
    print("NO")
```
## Bishop move

## Queen move

## Knight move

## Chocolate bar

## Leap year
