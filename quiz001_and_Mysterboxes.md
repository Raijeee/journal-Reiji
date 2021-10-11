# Quiz Number 1
![](3.9.png)

# Mystery Boxes of class
Kojiro_Months
'''.py
def conv(input1):
  output1 = ""
  if input1 == 1:
    output1 += "J"
  if input1 == 2:
    output1 += "F"
  if input1 == 3:
    output1 += "M"
  if input1 == 4:
    output1 += "A"
  if input1 == 5:
    output1 += "M"
  if input1 == 6:
    output1 += "J"
  if input1 == 7:
    output1 += "J"
  if input1 == 8:
    output1 += "A"
  if input1 == 9:
    output1 += "S"
  if input1 == 10:
    output1 += "O"
  if input1 == 11:
    output1 += "N"
  if input1 == 12:
    output1 += "D"
  if input1 > 12:
    output1 = "False"
  return output1

output1 = conv(10)
print(output1)
'''

Reiji_Factorial
'''.py
def mystery_box2(num):
    z=1
    x=1
    for i in range (num):
        z*=x
        x+=1
    return z
output2=mystery_box2(5)
print(output2)
'''

Nagisa_weird_average
