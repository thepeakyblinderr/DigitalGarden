---
time: 22:43
date: 2022-03-20 
tag: programming              
---


___
# Python
[Link for course](https://youtu.be/gfDE2a7MKjA)
[full course](https://youtu.be/aqvDTCpNRek)
[Another course](https://youtu.be/XKHEtdqhLK8)

___
to run - *python main.py*

# Basics
## if loop
```
if (age >18):
     this is inside if  (this is indent)
here it is out of loop 

```

```
# this is comment
```

ctrl+ / is shortcut to comment and uncomment

**Multiline comment**
![[Pasted image 20220321224603.png|300]]


## Import statement 
which already has been done by someone , available for free 

open windows powershell > ***pip install opencv.python***
not necessary that we should import package with the same name

import math

math is one of module

![[Pasted image 20220321230744.png]]

```
import math

print(math.gcd(3,6))
answer will be 3
```

to check modules go to [built in modules in python](https://docs.python.org/3/py-modindex.html)

```
a = 3

b = "sandesh"  --> this is string

c=32.4

```

## sum program
```
a = 369

b = "sandesh"

c= 32.4

print (a+3)
```

1. variable should start with _ or letter
2. variable cannot start with number
3. it can only contain alphanumeric character
	1. c* is not alphanumeric
4. variable are case sensitive
	

```
a = 32  this is number
a = "32" this string
```

to find type of variable type

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

typeA = type(b)

print(typeA)

here b is string

```

or

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

  

print(type(a))

here a is int


```


## Type casting
convert one thing into other
![[Pasted image 20220321235402.png]]
here string into "int"

# String
### Intro


![[Pasted image 20220322000053.png]]
![[Pasted image 20220322000107.png]]
 we can use triple quotes to write strings in certain fashion but this cant be done with double

###### to find the first character of string we can do that with the help of numbers 0,1,2,3,4,5,6,7,8....

^14db88

Ex 1
```
name = "harry"

print(name[2])

output === 'r'

```

Ex 2
```
name = "harry"
        01234

print(name[2:4])

output === it will include 2 and 3 means upto 4 only 
'rr'

```


### Slicing
***Characters should be (4-2)=2***

### Strip function
to slice/remove spaces

```
name = "             harry   "

print(name)

```
![[Pasted image 20220322103449.png]]
output is with spaces

to remove spaces we use strip function

```
name = "             harry   "

print(name.strip())
```
![[Pasted image 20220322103613.png]]
___

### To find length of string
```
name = "harry"

print(len(name))
```

### To convert into upper and lower
```
name = "harry"

# print(len(name))

print(name.upper())

print(name.lower())

```
![[Pasted image 20220322104239.png]]

### replace function
```
name = "harry"

print(name.replace("r","p"))
```
![[Pasted image 20220322104513.png]]

___

***To replace commas with space***

```
name = "harry, sandesh , wankhade"

print(name.replace(","," "))
```
___
### To concatenate

```
str= "sandesh"

str2 = " wankhade"

print(str + str2)
```
![[Pasted image 20220322111207.png]]
### To form template

*using format function*

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {} and he is friend of {}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {0} and he is friend of {1}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {1} and he is friend of {0}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322112616.png]]

 ***F string function***
```
name1= "sandesh"

name2= "tejas"

temp = f"this is a {name2} and he is friend of {name1}"

print(temp)
```
![[Pasted image 20220322113529.png]]
___

![[Pasted image 20220322113728.png]]
1.  power function
2. divides but return interger
3. remainder
___
>  we can use alt + arrow keys to move the code lines up and down


# Python collection
## List function
**to add value at the end of list we use .append()**
![[Pasted image 20220323111536.png]]

**to insert value at particular position**
![[Pasted image 20220323112532.png]]

**to remove value**
![[Pasted image 20220323112636.png]]

**to remove value from end**
![[Pasted image 20220323112727.png]]

**to remove value from end at position with the help of index value**
![[Pasted image 20220323113251.png]]

**to clear value**
![[Pasted image 20220323113437.png]]

## Tuple
major difference is that you can't change tuple item like list
otherwise all most all function we used for list can be used for tuple function too
![[Pasted image 20220323114602.png]]

we can **type cast** and then convert it into list and then assign/modify tuple



n
[Link for course](https://youtu.be/gfDE2a7MKjA)
[full course](https://youtu.be/aqvDTCpNRek)
[Another course](https://youtu.be/XKHEtdqhLK8)

___
to run - *python main.py*

# Basics
## if loop
```
if (age >18):
     this is inside if  (this is indent)
here it is out of loop 

```

```
# this is comment
```

ctrl+ / is shortcut to comment and uncomment

**Multiline comment**
![[Pasted image 20220321224603.png|300]]


## Import statement 
which already has been done by someone , available for free 

open windows powershell > ***pip install opencv.python***
not necessary that we should import package with the same name

import math

math is one of module

![[Pasted image 20220321230744.png]]

```
import math

print(math.gcd(3,6))
answer will be 3
```

to check modules go to [built in modules in python](https://docs.python.org/3/py-modindex.html)

```
a = 3

b = "sandesh"  --> this is string

c=32.4

```

## sum program
```
a = 369

b = "sandesh"

c= 32.4

print (a+3)
```

1. variable should start with _ or letter
2. variable cannot start with number
3. it can only contain alphanumeric character
	1. c* is not alphanumeric
4. variable are case sensitive
	

```
a = 32  this is number
a = "32" this string
```

to find type of variable type

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

typeA = type(b)

print(typeA)

here b is string

```

or

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

  

print(type(a))

here a is int


```


## Type casting
convert one thing into other
![[Pasted image 20220321235402.png]]
here string into "int"

# String
### Intro


![[Pasted image 20220322000053.png]]
![[Pasted image 20220322000107.png]]
 we can use triple quotes to write strings in certain fashion but this cant be done with double

###### to find the first character of string we can do that with the help of numbers 0,1,2,3,4,5,6,7,8....

^14db88

Ex 1
```
name = "harry"

print(name[2])

output === 'r'

```

Ex 2
```
name = "harry"
        01234

print(name[2:4])

output === it will include 2 and 3 means upto 4 only 
'rr'

```


### Slicing
***Characters should be (4-2)=2***

### Strip function
to slice/remove spaces

```
name = "             harry   "

print(name)

```
![[Pasted image 20220322103449.png]]
output is with spaces

to remove spaces we use strip function

```
name = "             harry   "

print(name.strip())
```
![[Pasted image 20220322103613.png]]
___

### To find length of string
```
name = "harry"

print(len(name))
```

### To convert into upper and lower
```
name = "harry"

# print(len(name))

print(name.upper())

print(name.lower())

```
![[Pasted image 20220322104239.png]]

### replace function
```
name = "harry"

print(name.replace("r","p"))
```
![[Pasted image 20220322104513.png]]

___

***To replace commas with space***

```
name = "harry, sandesh , wankhade"

print(name.replace(","," "))
```
___
### To concatenate

```
str= "sandesh"

str2 = " wankhade"

print(str + str2)
```
![[Pasted image 20220322111207.png]]
### To form template

*using format function*

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {} and he is friend of {}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {0} and he is friend of {1}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {1} and he is friend of {0}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322112616.png]]

 ***F string function***
```
name1= "sandesh"

name2= "tejas"

temp = f"this is a {name2} and he is friend of {name1}"

print(temp)
```
![[Pasted image 20220322113529.png]]
___

![[Pasted image 20220322113728.png]]
1.  power function
2. divides but return interger
3. remainder
___
>  we can use alt + arrow keys to move the code lines up and down


# Python collection
## List function
**to add value at the end of list we use .append()**
![[Pasted image 20220323111536.png]]

**to insert value at particular position**
![[Pasted image 20220323112532.png]]

**to remove value**
![[Pasted image 20220323112636.png]]

**to remove value from end**
![[Pasted image 20220323112727.png]]

**to remove value from end at position with the help of index value**
![[Pasted image 20220323113251.png]]

**to clear value**
![[Pasted image 20220323113437.png]]

## Tuple
major difference is that you can't change tuple item like list
otherwise all most all function we used for list can be used for tuple function too
![[Pasted image 20220323114602.png]]

we can **type cast** and then convert it into list and then assign/modify tuple



ing              
---

___
# Pytho---
time: 22:43
date: 2022-03-20 
tag: programming              
---

___
# Python
[Link for course](https://youtu.be/gfDE2a7MKjA)
[full course](https://youtu.be/aqvDTCpNRek)
[Another course](https://youtu.be/XKHEtdqhLK8)

___
to run - *python main.py*

# Basics
## if loop
```
if (age >18):
     this is inside if  (this is indent)
here it is out of loop 

```

```
# this is comment
```

ctrl+ / is shortcut to comment and uncomment

**Multiline comment**
![[Pasted image 20220321224603.png|300]]


## Import statement 
which already has been done by someone , available for free 

open windows powershell > ***pip install opencv.python***
not necessary that we should import package with the same name

import math

math is one of module

![[Pasted image 20220321230744.png]]

```
import math

print(math.gcd(3,6))
answer will be 3
```

to check modules go to [built in modules in python](https://docs.python.org/3/py-modindex.html)

```
a = 3

b = "sandesh"  --> this is string

c=32.4

```

## sum program
```
a = 369

b = "sandesh"

c= 32.4

print (a+3)
```

1. variable should start with _ or letter
2. variable cannot start with number
3. it can only contain alphanumeric character
	1. c* is not alphanumeric
4. variable are case sensitive
	

```
a = 32  this is number
a = "32" this string
```

to find type of variable type

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

typeA = type(b)

print(typeA)

here b is string

```

or

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

  

print(type(a))

here a is int


```


## Type casting
convert one thing into other
![[Pasted image 20220321235402.png]]
here string into "int"

# String
### Intro


![[Pasted image 20220322000053.png]]
![[Pasted image 20220322000107.png]]
 we can use triple quotes to write strings in certain fashion but this cant be done with double

###### to find the first character of string we can do that with the help of numbers 0,1,2,3,4,5,6,7,8....

^14db88

Ex 1
```
name = "harry"

print(name[2])

output === 'r'

```

Ex 2
```
name = "harry"
        01234

print(name[2:4])

output === it will include 2 and 3 means upto 4 only 
'rr'

```


### Slicing
***Characters should be (4-2)=2***

### Strip function
to slice/remove spaces

```
name = "             harry   "

print(name)

```
![[Pasted image 20220322103449.png]]
output is with spaces

to remove spaces we use strip function

```
name = "             harry   "

print(name.strip())
```
![[Pasted image 20220322103613.png]]
___

### To find length of string
```
name = "harry"

print(len(name))
```

### To convert into upper and lower
```
name = "harry"

# print(len(name))

print(name.upper())

print(name.lower())

```
![[Pasted image 20220322104239.png]]

### replace function
```
name = "harry"

print(name.replace("r","p"))
```
![[Pasted image 20220322104513.png]]

___

***To replace commas with space***

```
name = "harry, sandesh , wankhade"

print(name.replace(","," "))
```
___
### To concatenate

```
str= "sandesh"

str2 = " wankhade"

print(str + str2)
```
![[Pasted image 20220322111207.png]]
### To form template

*using format function*

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {} and he is friend of {}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {0} and he is friend of {1}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {1} and he is friend of {0}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322112616.png]]

 ***F string function***
```
name1= "sandesh"

name2= "tejas"

temp = f"this is a {name2} and he is friend of {name1}"

print(temp)
```
![[Pasted image 20220322113529.png]]
___

![[Pasted image 20220322113728.png]]
1.  power function
2. divides but return interger
3. remainder
___
>  we can use alt + arrow keys to move the code lines up and down


# Python collection
## List function
**to add value at the end of list we use .append()**
![[Pasted image 20220323111536.png]]

**to insert value at particular position**
![[Pasted image 20220323112532.png]]

**to remove value**
![[Pasted image 20220323112636.png]]

**to remove value from end**
![[Pasted image 20220323112727.png]]

**to remove value from end at position with the help of index value**
![[Pasted image 20220323113251.png]]

**to clear value**
![[Pasted image 20220323113437.png]]

## Tuple
major difference is that you can't change tuple item like list
otherwise all most all function we used for list can be used for tuple function too
![[Pasted image 20220323114602.png]]

we can **type cast** and then convert it into list and then assign/modify tuple



n
[Link for course](https://youtu.be/gfDE2a7MKjA)
[full course](https://youtu.be/aqvDTCpNRek)
[Another course](https://youtu.be/XKHEtdqhLK8)

___
to run - *python main.py*

# Basics
## if loop
```
if (age >18):
     this is inside if  (this is indent)
here it is out of loop 

```

```
# this is comment
```

ctrl+ / is shortcut to comment and uncomment

**Multiline comment**
![[Pasted image 20220321224603.png|300]]


## Import statement 
which already has been done by someone , available for free 

open windows powershell > ***pip install opencv.python***
not necessary that we should import package with the same name

import math

math is one of module

![[Pasted image 20220321230744.png]]

```
import math

print(math.gcd(3,6))
answer will be 3
```

to check modules go to [built in modules in python](https://docs.python.org/3/py-modindex.html)

```
a = 3

b = "sandesh"  --> this is string

c=32.4

```

## sum program
```
a = 369

b = "sandesh"

c= 32.4

print (a+3)
```

1. variable should start with _ or letter
2. variable cannot start with number
3. it can only contain alphanumeric character
	1. c* is not alphanumeric
4. variable are case sensitive
	

```
a = 32  this is number
a = "32" this string
```

to find type of variable type

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

typeA = type(b)

print(typeA)

here b is string

```

or

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

  

print(type(a))

here a is int


```


## Type casting
convert one thing into other
![[Pasted image 20220321235402.png]]
here string into "int"

# String
### Intro


![[Pasted image 20220322000053.png]]
![[Pasted image 20220322000107.png]]
 we can use triple quotes to write strings in certain fashion but this cant be done with double

###### to find the first character of string we can do that with the help of numbers 0,1,2,3,4,5,6,7,8....

^14db88

Ex 1
```
name = "harry"

print(name[2])

output === 'r'

```

Ex 2
```
name = "harry"
        01234

print(name[2:4])

output === it will include 2 and 3 means upto 4 only 
'rr'

```


### Slicing
***Characters should be (4-2)=2***

### Strip function
to slice/remove spaces

```
name = "             harry   "

print(name)

```
![[Pasted image 20220322103449.png]]
output is with spaces

to remove spaces we use strip function

```
name = "             harry   "

print(name.strip())
```
![[Pasted image 20220322103613.png]]
___

### To find length of string
```
name = "harry"

print(len(name))
```

### To convert into upper and lower
```
name = "harry"

# print(len(name))

print(name.upper())

print(name.lower())

```
![[Pasted image 20220322104239.png]]

### replace function
```
name = "harry"

print(name.replace("r","p"))
```
![[Pasted image 20220322104513.png]]

___

***To replace commas with space***

```
name = "harry, sandesh , wankhade"

print(name.replace(","," "))
```
___
### To concatenate

```
str= "sandesh"

str2 = " wankhade"

print(str + str2)
```
![[Pasted image 20220322111207.png]]
### To form template

*using format function*

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {} and he is friend of {}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {0} and he is friend of {1}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {1} and he is friend of {0}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322112616.png]]

 ***F string function***
```
name1= "sandesh"

name2= "tejas"

temp = f"this is a {name2} and he is friend of {name1}"

print(temp)
```
![[Pasted image 20220322113529.png]]
___

![[Pasted image 20220322113728.png]]
1.  power function
2. divides but return interger
3. remainder
___
>  we can use alt + arrow keys to move the code lines up and down


# Python collection
## List function
**to add value at the end of list we use .append()**
![[Pasted image 20220323111536.png]]

**to insert value at particular position**
![[Pasted image 20220323112532.png]]

**to remove value**
![[Pasted image 20220323112636.png]]

**to remove value from end**
![[Pasted image 20220323112727.png]]

**to remove value from end at position with the help of index value**
![[Pasted image 20220323113251.png]]

**to clear value**
![[Pasted image 20220323113437.png]]

## Tuple
major difference is that you can't change tuple item like list
otherwise all most all function we used for list can be used for tuple function too
![[Pasted image 20220323114602.png]]

we can **type cast** and then convert it into list and then assign/modify tuple



 Pytho---
time: 22:43
date: 2022-03-20 
tag: programming              
---

___
# Python
[Link for course](https://youtu.be/gfDE2a7MKjA)
[full course](https://youtu.be/aqvDTCpNRek)
[Another course](https://youtu.be/XKHEtdqhLK8)

___
to run - *python main.py*

# Basics
## if loop
```
if (age >18):
     this is inside if  (this is indent)
here it is out of loop 

```

```
# this is comment
```

ctrl+ / is shortcut to comment and uncomment

**Multiline comment**
![[Pasted image 20220321224603.png|300]]


## Import statement 
which already has been done by someone , available for free 

open windows powershell > ***pip install opencv.python***
not necessary that we should import package with the same name

import math

math is one of module

![[Pasted image 20220321230744.png]]

```
import math

print(math.gcd(3,6))
answer will be 3
```

to check modules go to [built in modules in python](https://docs.python.org/3/py-modindex.html)

```
a = 3

b = "sandesh"  --> this is string

c=32.4

```

## sum program
```
a = 369

b = "sandesh"

c= 32.4

print (a+3)
```

1. variable should start with _ or letter
2. variable cannot start with number
3. it can only contain alphanumeric character
	1. c* is not alphanumeric
4. variable are case sensitive
	

```
a = 32  this is number
a = "32" this string
```

to find type of variable type

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

typeA = type(b)

print(typeA)

here b is string

```

or

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

  

print(type(a))

here a is int


```


## Type casting
convert one thing into other
![[Pasted image 20220321235402.png]]
here string into "int"

# String
### Intro


![[Pasted image 20220322000053.png]]
![[Pasted image 20220322000107.png]]
 we can use triple quotes to write strings in certain fashion but this cant be done with double

###### to find the first character of string we can do that with the help of numbers 0,1,2,3,4,5,6,7,8....

^14db88

Ex 1
```
name = "harry"

print(name[2])

output === 'r'

```

Ex 2
```
name = "harry"
        01234

print(name[2:4])

output === it will include 2 and 3 means upto 4 only 
'rr'

```


### Slicing
***Characters should be (4-2)=2***

### Strip function
to slice/remove spaces

```
name = "             harry   "

print(name)

```
![[Pasted image 20220322103449.png]]
output is with spaces

to remove spaces we use strip function

```
name = "             harry   "

print(name.strip())
```
![[Pasted image 20220322103613.png]]
___

### To find length of string
```
name = "harry"

print(len(name))
```

### To convert into upper and lower
```
name = "harry"

# print(len(name))

print(name.upper())

print(name.lower())

```
![[Pasted image 20220322104239.png]]

### replace function
```
name = "harry"

print(name.replace("r","p"))
```
![[Pasted image 20220322104513.png]]

___

***To replace commas with space***

```
name = "harry, sandesh , wankhade"

print(name.replace(","," "))
```
___
### To concatenate

```
str= "sandesh"

str2 = " wankhade"

print(str + str2)
```
![[Pasted image 20220322111207.png]]
### To form template

*using format function*

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {} and he is friend of {}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {0} and he is friend of {1}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {1} and he is friend of {0}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322112616.png]]

 ***F string function***
```
name1= "sandesh"

name2= "tejas"

temp = f"this is a {name2} and he is friend of {name1}"

print(temp)
```
![[Pasted image 20220322113529.png]]
___

![[Pasted image 20220322113728.png]]
1.  power function
2. divides but return interger
3. remainder
___
>  we can use alt + arrow keys to move the code lines up and down


# Python collection
## List function
**to add value at the end of list we use .append()**
![[Pasted image 20220323111536.png]]

**to insert value at particular position**
![[Pasted image 20220323112532.png]]

**to remove value**
![[Pasted image 20220323112636.png]]

**to remove value from end**
![[Pasted image 20220323112727.png]]

**to remove value from end at position with the help of index value**
![[Pasted image 20220323113251.png]]

**to clear value**
![[Pasted image 20220323113437.png]]

## Tuple
major difference is that you can't change tuple item like list
otherwise all most all function we used for list can be used for tuple function too
![[Pasted image 20220323114602.png]]

we can **type cast** and then convert it into list and then assign/modify tuple



n
[Link for course](https://youtu.be/gfDE2a7MKjA)
[full course](https://youtu.be/aqvDTCpNRek)
[Another course](https://youtu.be/XKHEtdqhLK8)

___
to run - *python main.py*

# Basics
## if loop
```
if (age >18):
     this is inside if  (this is indent)
here it is out of loop 

```

```
# this is comment
```

ctrl+ / is shortcut to comment and uncomment

**Multiline comment**
![[Pasted image 20220321224603.png|300]]


## Import statement 
which already has been done by someone , available for free 

open windows powershell > ***pip install opencv.python***
not necessary that we should import package with the same name

import math

math is one of module

![[Pasted image 20220321230744.png]]

```
import math

print(math.gcd(3,6))
answer will be 3
```

to check modules go to [built in modules in python](https://docs.python.org/3/py-modindex.html)

```
a = 3

b = "sandesh"  --> this is string

c=32.4

```

## sum program
```
a = 369

b = "sandesh"

c= 32.4

print (a+3)
```

1. variable should start with _ or letter
2. variable cannot start with number
3. it can only contain alphanumeric character
	1. c* is not alphanumeric
4. variable are case sensitive
	

```
a = 32  this is number
a = "32" this string
```

to find type of variable type

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

typeA = type(b)

print(typeA)

here b is string

```

or

```
a = 3

b = "sandesh"

c = 32.4

print (a+3)

  

print(type(a))

here a is int


```


## Type casting
convert one thing into other
![[Pasted image 20220321235402.png]]
here string into "int"

# String
### Intro


![[Pasted image 20220322000053.png]]
![[Pasted image 20220322000107.png]]
 we can use triple quotes to write strings in certain fashion but this cant be done with double

###### to find the first character of string we can do that with the help of numbers 0,1,2,3,4,5,6,7,8....

^14db88

Ex 1
```
name = "harry"

print(name[2])

output === 'r'

```

Ex 2
```
name = "harry"
        01234

print(name[2:4])

output === it will include 2 and 3 means upto 4 only 
'rr'

```


### Slicing
***Characters should be (4-2)=2***

### Strip function
to slice/remove spaces

```
name = "             harry   "

print(name)

```
![[Pasted image 20220322103449.png]]
output is with spaces

to remove spaces we use strip function

```
name = "             harry   "

print(name.strip())
```
![[Pasted image 20220322103613.png]]
___

### To find length of string
```
name = "harry"

print(len(name))
```

### To convert into upper and lower
```
name = "harry"

# print(len(name))

print(name.upper())

print(name.lower())

```
![[Pasted image 20220322104239.png]]

### replace function
```
name = "harry"

print(name.replace("r","p"))
```
![[Pasted image 20220322104513.png]]

___

***To replace commas with space***

```
name = "harry, sandesh , wankhade"

print(name.replace(","," "))
```
___
### To concatenate

```
str= "sandesh"

str2 = " wankhade"

print(str + str2)
```
![[Pasted image 20220322111207.png]]
### To form template

*using format function*

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {} and he is friend of {}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {0} and he is friend of {1}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322111858.png]]

```
name1= "sandesh"

name2= "tejas"

temp = "this is a boy named {1} and he is friend of {0}".format(name1,name2)

print(temp)
```
![[Pasted image 20220322112616.png]]

 ***F string function***
```
name1= "sandesh"

name2= "tejas"

temp = f"this is a {name2} and he is friend of {name1}"

print(temp)
```
![[Pasted image 20220322113529.png]]
___

![[Pasted image 20220322113728.png]]
1.  power function
2. divides but return interger
3. remainder
___
>  we can use alt + arrow keys to move the code lines up and down


# Python collection
## List function
**to add value at the end of list we use .append()**
![[Pasted image 20220323111536.png]]

**to insert value at particular position**
![[Pasted image 20220323112532.png]]

**to remove value**
![[Pasted image 20220323112636.png]]

**to remove value from end**
![[Pasted image 20220323112727.png]]

**to remove value from end at position with the help of index value**
![[Pasted image 20220323113251.png]]

**to clear value**
![[Pasted image 20220323113437.png]]

## Tuple
major difference is that you can't change tuple item like list
otherwise all most all function we used for list can be used for tuple function too
![[Pasted image 20220323114602.png]]

we can **type cast** and then convert it into list and then assign/modify tuple



