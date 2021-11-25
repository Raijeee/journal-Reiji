![](quiz013.jpeg)
```.py
food = ["bread", "pasta", "rice"]
electronics = ["ipad","phone","computer"]
liquor = ["beer","vodka","gin"]

def total (item, price):
    i=1
    total=[]
    for i in range (len(item)):
        if item[i] in food:
            total=price[i]*1.1
        if item [i] in electronics:
            total=price[i]
        if item [i] in liquor:
            total=price[i]
        else:
            user=input(f"What category is {item[i]} food, electronics, liquor")
            user.append(item[i])
    return total
```
