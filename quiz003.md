```.py
def rangePatterN(num):
    n=-1
    a=""
    for i in range (100):
        if n < num:
            n+=1
        else:
            n=0
        a+=str(n)+","
    return a
a=rangePatterN(10)
print(a)
```


--------------------------------------------------------------------------------------------------------------------------------------------------------------------

```.py
def agelist(age):
    n=0
    sum=0
    a=""
    for i in range (100):
        if n < age:
            n+=1
        else:
            n=1
        a+=str(n)+","
    return a
a=agelist(10)
print(a)
```
