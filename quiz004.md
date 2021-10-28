# Quiz 004

```.py
def perfectN(num):
    a=[]
    b=0
    i=1
    while i!=num:
        if num%i==0:
            a.append(i)
            b+=i
        i+=1
    if b==num:
        c="True"
    else:
        c="False"
    return a, c
a=perfectN(6)
print(a)
```
