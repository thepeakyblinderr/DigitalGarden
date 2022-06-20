# Randomization
- Games is biggest category
- Python uses *Mersenne Twister* for randomization 
	- Watch video on Khan academy

## randint() function
- random module is [[python module]]
```py
import random
# int
random_num = random.randint(1,10)
print(random_num)
# float
random_float = random.random()
print(random_float)
```

## why random.randint ?
- we are using random module and randint is the function that belongs to random module
- random.random( ) gives value between **0 to 1** only

## Print random decimal in between 1 to 10
```py
import random
# int
random_num = random.randint(1,10)
print(random_num)
# float
random_float = random.random()
print(random_float)
value1 = input("do you want to genrate random decimal number between 1 to 10 ? Y or N").upper()
if (value1=='Y'):
  print(random_num + random_float)
elif (value1=='N'):
  print("as you wish mate but don'tcome back here and waste my time")   
else:
 print("error")

```

## Print random decimal in between 1 to 10
```py
import random
# int
random_num = random.randint(1,10)
print(random_num)
# float
random_float = random.random()
print(random_float)
value1 = input("do you want to genrate random decimal number between 1 to 10 ? Y or N").upper()
if (value1=='Y'):
  print(random_float*5)
elif (value1=='N'):
  print("as you wish mate but don'tcome back here and waste my time")   
else:
 print("error")
```

## head or tails programm
```py
import random

random_num = random.randint(0,1)
if (random_num==0):
  print("Heads")
else:
  print("Tails")

```