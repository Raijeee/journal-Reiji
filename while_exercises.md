## List of squares
For a given integer N, print all the squares of integer numbers where the square is less than or equal to N, in ascending order.

```.py
n= int(input())
for i in range (1,100):
    if n<i**2:
        break
    else:
        print(i**2)
```
![](3.1.png)
## Least divisor
Given an integer not less than 2. Print its smallest integer divisor greater than 1.
```.py
n = int(input())
i=2
while n%i !=0:
    i+=1
print(i)
```
![](3.2.png)
## The power of two
For a given integer N, find the greatest integer x where 2x is less than or equal to N. Print the exponent value and the result of the expression 2x.
Don't use the operation **.

```.py
n=int(input())
i=2
l=0
while n>=i:
    i*=2
    l+=1
    
print(l , i//2)
```
![](3.3.png)
## Morning jog
As a future athlete you just started your practice for an upcoming event. Given that on the first day you run x miles, and by the event you must be able to run y miles.
Calculate the number of days required for you to finally reach the required distance for the event, if you increases your distance each day by 10% from the previous day.

Print one integer representing the number of days to reach the required distance.

```.py
x = int(input())
y= int(input())
z=1
while y>x:
    x*=1.1
    z+=1
print(z)
```
![](3.4.png)
## The length of the sequence
Given a sequence of non-negative integers, where each number is written in a separate line. Determine the length of the sequence, where the sequence ends when the integer is equal to 0. Print the length of the sequence (not counting the integer 0). The numbers following the number 0 should be omitted.

```.py
i=1
x=0
while i!=0:
    i=int(input())
    x+=1
print(x-1)
```
![](3.5.png)
## The sum of the sequence
Determine the sum of all elements in the sequence, ending with the number 0.

```.py
i=1
x=0
while i!=0:
    i=int(input())
    x+=i
print(x)
```
![](3.6.png)
## The average of the sequence
Determine the average of all elements of the sequence ending with the number 0.

```.py
i=1
x=-1
y=0
while i!=0:
    i=int(input())
    x+=1
    y+=i
print(y/x)
```
![](3.7.png)
## The maximum of the sequence
A sequence consists of integer numbers and ends with the number 0. Determine the largest element of the sequence.

```.py
i=1
x=0
while i!=0:
    i=int(input())
    if i>x:
        x=i
print(x)
```
![](3.8.png)
