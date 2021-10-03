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

# Mystery Box 3

```.py

```
