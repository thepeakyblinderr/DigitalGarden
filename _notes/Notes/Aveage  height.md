```py
from numpy import average

  
  

list = []

n = int(input("enter the length of list"))

  

for i in range(n):

    x = int(input("enter ages of studnet"))

    list.append(x)

  

sum = 0

for i in range(n):

    sum = sum + list[i]

average = sum/n

print(average)
```

OR 
```py
from numpy import average

  
  

list = []

n = int(input("enter the length of list"))

  

for i in range(n):

    x = int(input("enter ages of studnet"))

    list.append(x)

  

print(average(list))
```