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
olleH
olleh

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
[Reiji]
[Nishikawa]
[gmail.com]

# Mystery Box 4

```.py
def mystery_box4(input_list:list):
    avg = 0
    filtered_list = []
    for i in range(len(input_list)):
        if input_list[i] < 8:
            avg += input_list[i]
            filtered_list.append(input_list[i])
        return (avg / len(input_list)), filtered_list
input=[7,4,5,6,7,8]
output4 = mystery_box4(input)
print(output4)

```

[5.8] [7,4,5,6,7]
