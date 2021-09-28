## Strange Numbers: Given a number as a String N. Multiply all of its digits, and repeat the same with the product obtained till the product consists of only one digit. Output the number of steps taken to do so.


```.py
a = input("What is your number? > ")
counter = 0
while int(a) > 9:
  b = int(int(a)/10)
  c = int(N) - (tens*10)
 a = b*c
  counter +=1

print(counter)
```
