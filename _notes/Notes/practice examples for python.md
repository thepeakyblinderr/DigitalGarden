# How to check it is prime or not 
we take *range* from **1 to num+1** because it will consider till 1,2,3,4 only but we want 5 too so we add 1

```py
num = int(input("enter number"))

count = 0

  

if num>1:

    for i in range(1,num+1):

        if (num%i)==0:

            count=count+1

    if count == 2:

        print("prime")

    else :

        print("not prime")
```

# finding factorial of number
```py
  

from math import factorial

  
  

num = int(input("enter a number"))

factorial = 1

  

if num<0:

    print("not defined")

elif num == 0:

    print("it is 1")

else :

    for i in range(1,num+1):

        factorial=factorial*i

    print(f"factorial is {factorial}")
```

# Print Fibonacci Series
Fibonacci number is sum of two preceding number

```py
# 0 1 1 2 3 5 8 13 21 34

  

n1=0

n2=1

print(n1) #0

print(n2) #1

  

for i in range(2,10):

    sum = n1+n2

    print(sum) #1

    n1=n2

    n2=sum

```

# Find Sum Of Elements in an Array
[[Array in python]]

```py
from array import *

  

arr = array('i',[])

n = int(input("enter the length of array"))

for i in range(n):

    x = int(input("enter the next value"))

    arr.append(x)

print(arr)

print(sum(arr))
```

# Print index number of value in array 
```py
from array import *

  

arr = array('i',[])

n = int(input("enter the length of array"))

for i in range(n):

    x = int(input("enter the next value"))

    arr.append(x)

print(arr)

print(sum(arr))

  

val = int(input("enter value"))

k=0

for e in arr:

    if e==val:

        print(k)

        break

  

    k=k+1
```

#  Find Maximum & Minimum Elements in an Array

```py
from array import *

  

arr = array('i',[])

n = int(input("enter the length of array"))

for i in range(n):

    x = int(input("enter the next value"))

    arr.append(x)

print(arr)

  

max = arr[0]

for i in range(1,n):

    if arr[i]>max:

        max = arr[i]

print(f"max value is {max}")

  

min = arr[0]

for i in range(1,n):

    if arr[i]<min:

        min = arr[i]

print(f"min value is {min}")
``` 
# How to take a user input for list in python
```py
list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)
```

# Counting number of elements in list
```py
list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

count = 0

for i in list:

    count=count+1

print(count)
```

or

```py
  

length = len(list)

print(f"length of list is {length}")
```

# Swapping first and last
```py
list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

list[0],list[-1]=list[-1],list[0]

print(list)
```

# swapping any number
```py
list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

pos1 = int(input("which you want to interchange ?"))

pos2 = int(input("with whom ?"))

  

list[pos1-1],list[pos2-1]=list[pos2-1],list[pos1-1]

print(list)
```

# How To Remove Nth occurrence of the word from a List
```py
list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = str(input("enter value"))

    list.append(x)

  

print(list)

  

word = "geek"

count = 0

c=2

for i in range(0, len(list)-1):

    if (list[i]==word):

        count=count+1

        if count==c:

            del list[i]

  

print(list)
```

# How To Search an Element in a List
```py
from cgi import print_environ
    

list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

ele = 4

flag = 0

  

for i in range(0,len(list)-1):

    if list[i]==ele:

        print("found it")

        flag=1

        break

if (flag==0):

    print("we lost bro")
```

or 
```py
from cgi import print_environ


list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

ele = 4

  

if (ele in list):

    print("wefounf it man")

else:

    print("nope go back to reality")
```

# How To Clear a List
```py
from cgi import print_environ

  
  

list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

print("do you want to clear list ? y or n")

x = str(input())

  

if (x.lower()=="y"):

    list.clear()

    print(list)

else:

    print(list)

```

# How To Reverse a List
```py

list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

print("do you want to reverse list ? y or n")

x = str(input())

  

if (x.lower()=="y"):

    list.reverse()

    print(list)

else:

    print(list)
```

# how to copy list
```py
list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

mylist_copy = list.copy()

print(mylist_copy)
```


# Count Occurrences of an element in a list
```py
from itertools import count

  
  

list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

x = int(input("what you nat to find"))

count = 0

  

for ele in list:

    if (ele==x):

        count= count+1

print(f"no of occurences{count}")
```

or 
```py
from itertools import count


list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

x = int(input("what you nat to find"))

count = 0

occur = list.count(x)

print(f"no of occurences {occur}")
```

#  Find Sum of Elements in the List
```py
from itertools import count

  
  

list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

sum = 0

for i in range(0,len(list)):

    sum=sum+list[i]

  

print(sum)
```

or 

```py
from itertools import count

  
  

list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

print(sum(list))
```

# Multiply All Numbers in the List
```py
from itertools import count

  
  

list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

fact=1

for i in range(0,len(list)):

    fact=fact*list[i]

  

print(fact)
```

# Find Smallest & Largest Numbers in a List
```py
from itertools import count

  
  

list = []

n = int(input("Enter the length of list"))

  

for i in range(n):

    x = int(input("enter value"))

    list.append(x)

  

print(list)

  

small=list[0]

for i in range(1,len(list)):

    if list[i]<small:

        small=list[i]

  

print(small)
```