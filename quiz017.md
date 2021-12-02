![](quiz017.jpeg)

```.py
def triangle(s1,s2,s3):
    out="False"
    if s1+s2>s3 and s1+s3>s2 and s2+s3>s1:
        out="True"
    return out

a=triangle(1,3,9)
b=triangle(23,24,25)

print(a)
print(b)
```
![](quiz017out.jpg)
