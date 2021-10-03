# Mystery Box 1

```.py
def mystery_box1 (word,capital):

    if capital is True:
        final = word.lower()[::-1]
    else:
        final= word[::-1]
    return final

output = mystery_box1("Hello", False)
print(output)

output2 = mystery_box1("Hello", True)
print(output2)
```

# Mystery Box 2

```.py
def mystery_box2 (email):
    str(email)
    firstname=email.split("@")[0:1:]
    com=email.split("@")[1::]
    return str(f"{firstname}\n{com}")

output3 = mystery_box2("reiji.nishikawa@gmail.com")
print(output3)
```

# Mystery Box 4

```.py
def mystery_box4(v1,v2,v3,v4,v5,v6,v7):
    total=v1+v2+v3+v4+v5+v6+v7
    num=7
    if v1>7:
        total-v1
        num -= 1
    if v2>7:
        total-v2
        num -= 1
    if v3>7:
        total-v3
        num -= 1
    if v4>7:
        total-v4
        num -= 1
    if v5>7:
        total-v5
        num -= 1
    if v6>7:
        total-v6
        num -= 1
    if v7>7:
        total-v7
        num -= 1
    average=total/num
    return average

result = ibscore(5,6,3,8,1,7,9)
print(result)
```
