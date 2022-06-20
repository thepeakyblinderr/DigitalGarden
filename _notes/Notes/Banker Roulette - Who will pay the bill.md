# Using random() concept

```py


import random

names_string = input("Give me everybody's names, separated by a comma. ")
names = names_string.split(", ")

i = random.randint(0,len(names)-1)
print(f"{names[i]} is going to buy the meal today!")

```

# Using choice function 
```py
import random

names_string = input("Give me everybody's names, separated by a comma. ")
names = names_string.split(", ")

random = random.choice(names)
print(f"{random} is going to buy the meal today!")

```