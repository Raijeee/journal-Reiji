```.py
def strange_add (number,number2):
    if (number+number2)%2==1:
        number=0
    else:
        number+=number2
    return number
output=strange_add(strange_add (5,8),strange_add(4,2))
print(output)



def black_box (l1,l2):
    if l2>l1:
        l1=l1
    else:
        l1=l2
    return l1
output2=black_box("z","b")
print(output2)



def strange_box (num):
    if num <=26:
        num=chr(num+64)
    else:
        num="?"
    return num
output3=strange_box(9)
print(output3)



output4=black_box(strange_box(strange_add(5,11)),strange_box(strange_add(10,2)))
print(output4)

```
