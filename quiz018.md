
![](quiz018.jpeg)
```.py
def sum67 (num):
    out=0
    skip=False
    for i in range (len(num)):
        if num[i]==6:
            skip=True
        if skip==False:
            out+=num[i]
        if num[i]==7:
            skip=False
    return out
a=sum67([1,2,12,6,92,4,7,10])
print(a)
```
![](quiz018out.png)