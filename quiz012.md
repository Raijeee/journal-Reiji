## Given an list of words, find the average word length.
 
## Example:

## wordlength(["home","car","travel","beach"])→4.5
## wordlength(["sun","sat","cut","can"]) → 3
## wordlength("police", "abacus"]) → 6


![](quiz012.jpeg)

```.py
def wordlength(list):
    list=0
    out=0
    i=0
    for i in range (len(list)):
        list += len(list[i])
    out=list/len(list)
    return out

out1= wordlength(["Hello", "car", "travel","beach"])
print(out1)
```
## Output:
![](quiz012out.png)

## Flowchart:
![](quiz012flow.jpg)
