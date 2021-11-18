```.py
def wordlength(list):
    a=0
    b=0
    i=0
    for i in range (len(list)):
        a += len(list[i])
    b=a/len(list)
    return b

a= wordlength(["Hello", "car", "travel","beach"])
print(a)
```

output: 4.75
