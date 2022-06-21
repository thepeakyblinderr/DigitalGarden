```toc
```

https://youtu.be/zdWycfoeCRE


# Day 1 - Beginner - Working with Variables in Python to Manage Data
## String manipulation
if i want to print  Hello World three time I'll have to use print function *three times in three rows*
but instead we can use \n

```py
print("hello world\nhello world")
```
 **To run program we can use `Ctrl+Enter`**

### Concatenate
```py
print("hello"+"sandesh")
```
 there won't be any space in between
 output - hellosandesh

```py
print("hello"+" sandesh")
```
now there will be space
OR
```py
print("hello"+" "+"sandesh")
```

**Code intelligence function helps you with Auto complete** 

DeBug name has interesting story behind it

```py
print('print("hello"+" "+"sandesh")')
```

output - print("hello"+" "+"sandesh")
___

```py
print(("New lines can be created with a backslash and n.")
```
this will show parsing error because compiler will think that we are still going to write something because we have incomplete parenthesis

___
```py
print("String Concatenation is done with the "+" sign.")
```

output - String Concatenation is done with the  sign.
here we can see + sign is missing
why ?
because it interpret it as **concatenate**

```py
print('String Concatenation is done with the "+" sign.')
```
 now by changing from " " to ' ' it consider whole thing as one string
 output - String Concatenation is done with the "+" sign

### The Python Input Function
If it is not showing any orange arrow it means it is paused right now

```py
print("hello " + input("what is your name?"))
```
output - what is your name?sandesh
hello sandesh

### [Thonny](https://thonny.org/) is used to see how program is executed step by step
https://pythontutor.com/ can also be used


`# to turn it into a comment`
it is a good practice to use comments so that even if you visit a code after years your future self will be able to understand it

Shortcut for comment - `ctrl+/` but only after selecting code you want to comment out

### Print number of characters in input
```py
print(len(input("what is your name ?")))
```

### Python variable
```py
name = input("what is your name ? ")
print(name)
```

`what is your name ? sandesh`
`sandesh`

---
```py
name = "sandesh"
print(name)

name = "wankhade"
print(name)
```

`sandesh`
`wankhade`

___
```py
name = input("whats my name")
length = len(name)
print(length)

```

`whats my name sandesh`
`8`

---
### Switch the number
```py
a = input("a:")
b = input("b:")

c=a
a=b
b=c

print("a:"+a)
print("b:"+b)
```

`a:3`
`b:5`
`a:5`
`b:3`

___
### Variable Naming
- we can't have space between variable name if we want to seperate use `_`
- we can use numbers in variable name but they can't be at the beginning of variable name

### Day 1 project
### Band name generator

```py
city_name = input("enter your city name\n")
pet_name = input("enter your pet name\n")
print("Your band name is "+city_name +" "+ pet_name)
```

`enter your city name`
`mumbai`
`enter your pet name`
`sandy`
`Your band name is mumbai sandy`

# Day 2 - Beginner - Understanding Data Types and How to Manipulate Strings
## Python Primitive Data Types
### String
#### Subscript
Method of pulling out certain element from string 
It starts from 0

```py
print("hello"[0])
```

`0`
___

### Integer
"132" is treated as text only as long as it is inside double quotes

123,456,790 this 123 million written with commas
we use commas for simplification only 
this same commas can be replaced with `_`

```py
print(123_456_789)
```

`123456789`

---
### Float
ex - 3.14 
`mystery = 734_529.678`
this is still float because that underscore is just for us to understand
___

### Boolean
only two values 
**True and False**
*they start with capital letter*
___
## Type Error, Type Checking and Type Conversion
### Type error
We cannot **concatenate** string with number

```py
num_char = len(input("what is your name?"))
print("Your name has " + num_char + "characters")
```

will show error

### Type checking
type() function to check data type

```py
num_char = len(input("what is your name?"))
# print("Your name has " + num_char + "characters")
print(type(num_char))
```

`what is your name?adesh`
`<class 'int'>`

---
### Type casting
```py
num_char = len(input("what is your name?"))

new_num_char = str(num_char)

print("Your name has " + new_num_char + " characters")

```

`what is your name?sandesh`
`Your name has 7 characters`

here it is converted from INT to STRING
___

### Concepts

```py
print(70 + float("100.5"))
```

`170.5`
here string is converted into float and then added 

```py
print(str(70)+str(110))
```

`70110`
___
### Example
### Write a program that adds the digits in a 2 digit number. e.g. if the input was 35, then the output should be 3 + 5 = 8

```py


two_digit_number = input("Type a two digit number: ")



str(two_digit_number)

a = two_digit_number[0]

b = two_digit_number[1]

  

new_a = int(a)

new_b = int(b)

  

print(new_a + new_b)
```

## Mathematical Operations in Python

---
whenever we divide in python we always  end up with **floating number**

**Exponent**
`2**2` is 2 to the power 2

### Order of priority
**PEMDAS**
	parentheses ()
	exponents **
	multiply *
	division /
	addition +
	substraction -

It moves from LEFT to RIGHT
Check using **Thonny**

### BMI calculator
```py

 height = input("enter your height in m: ")

 weight = input("enter your weight in kg: ")

  

 print(type(weight))

 print(type(height))

  

 a = int(weight)

 b = float(height)

  

 bmi = a/b**2

 print((bmi))

```

## Number Manipulation and F Strings in Python
### Rounding of number
if number is 2.5 then round off to 3
to do that `round()` function

```py
print(round(8/3))
```

`3`

#### Number of places you want to round it to
```py
print(round(8/3,2))
```

`2.67`

here we round it off to 2 places

OR

```py
print(round(2.666667,2))
```

`2.67`

---

If i don't want to convert it into integer using function then directly use `//`
```py
print(8//3)
```
`2`

### F string
if there are different data types , it is painful to convert one data into another and use `+` sign every time , to avoid that we use **f- string**
```py
score = 0
height = 1.8
isWinning = True

print(f"your score is {score},your height is {height}, are you winning son {isWinning}")
```
`your score is 0,your height is 1.8, are you winning son True`

#### Create a program using maths and f-Strings that tells us how many days, weeks, months we have left if we live until 90 years old

```py
age = input("What is your current age?")


int_age = int(age)

months_rem = 90*12-int_age*12

weeks_rem = 90*52-int_age*52

days_rem = 90*365-int_age*365

  

print(f"you have {days_rem} days, {weeks_rem} weeks, and {months_rem} months left")

```
`You have 12410 days, 1768 weeks, and 408 months left.`
here we converted age **data type string** to int by storing it in **int_age**
 
#### Day 2 project
```py
print("Welcome to the tip calculator!")
bill = float(input("What was the total bill? $"))
tip = int(input("How much tip would you like to give? 10, 12, or 15? "))
people = int(input("How many people to split the bill?"))

tip_as_percent = tip / 100
total_tip_amount = bill * tip_as_percent
total_bill = bill + total_tip_amount
bill_per_person = total_bill / people
final_amount = round(bill_per_person, 2)
final_amount = "{:.2f}".format(bill_per_person)
print(f"Each person should pay: ${final_amount}")
```

`What was the total bill?150`
`How much tip would you like to give?12`
`How many people to split the bill?5`
`you have to pay 33.60`

here we programmed so that it has 2 decimal point but it is only showing 33.6 instead of 33.60
it is not mathematical error it is just **formatting** error
```
final_amount = "{:.2f}".format(bill_per_person)
```

**YOU CAN SAVE THE REPLIT PROGRAMM WITH THE LINK ON YOUR MOBILE**

# Day 3 - Beginner - Control Flow and Logical Operators
## If else statement
indent after the **if** is considered as block of code

### Rollercoaster problem
```py
print("Welcome to the rollercoaster!")
height = int(input("What is your height in cm? "))

if height>=180:
  print("ride bitch")
else:
  print("fuck off bitch")
```

### To draw the flowchart use Draw.io



### Comparison operator
```
1. >
2. <
3. >=
4. <=
5. ==
6. !=

```

= to assign
== to compare/equality
## odd or even
```python

number = int(input("Which number do you want to check? "))

if (number%2)==0:
  print("even")
else:
  print("odd")
```

## Nested if statements and elif statements
- if else in another if else statement

```python
print("Welcome to the rollercoaster!")
height = int(input("What is your height in cm? "))

if height>=180:
  print("ride bitch")
  age = int(input("what is your age ?"))
  
  if age >= 18:
   print("give me 12")
  else :
    print("give me 7")
else:
  print("fuck off bitch")
```

## elif statement 
to check if in between 12-18 using elif
we can use as many **elif** condition as we like

```python
print("Welcome to the rollercoaster!")
height = int(input("What is your height in cm? "))

if height>=180:
  print("ride bitch")
  age = int(input("what is your age ?"))

  if age<12:
    print("please 5")
  elif age <= 18:
   print("give me 7")
  else :
    print("give me 12")
else:
  print("fuck off bitch")
```

## BMI 2.0
```python

height = float(input("enter your height in m: "))
weight = float(input("enter your weight in kg: "))

bmi = float(weight/height**2)
print(f"your bmi is {round(bmi)}")

if bmi < 18.5 :
 print("you are underweight")
elif bmi < 25 :
   print("you have normal weight")
elif bmi < 30 :
   print("you are slighty overweight")
elif bmi < 35 :
   print("you are obese")
else :
 print("you are clinically obese")
  

# - Under 18.5 they are underweight
# - Over 18.5 but below 25 they have a normal weight
# - Over 25 but below 30 they are slightly overweight
# - Over 30 but below 35 they are obese
# - Above 35 they are clinically obese


```

## Leap year exercise
```python

year = int(input("Which year do you want to check? "))


if year % 400 == 0:
 print("Leap Year")
elif year % 100 == 0:
 print("Not leap year")
elif year % 4 == 0:
 print("Leap year")
else:
 print("not leap year")

```


## Multiple If Statements in Succession
- here there are multiple **if** which check each condition it is false then it moves onto the next **if** statement
```python
if cond a:
 do a
if cond b:
 do b
if cond c:
 do c
```

### Roller-coaster program
```python
print("welcome to the rollercoaster ride")
height = int(input("what is you height"))
if height > 120:
  print("you can ride")
  
  age = int(input("what is your age?"))
  if age < 12:
    bill = 5
    print(f"your bill is {bill}")
  elif age <= 18:
    bill = 7
    print(f"your bill is {bill}")
  else :
    bill = 12
    print(f"your bill is {bill}")
  wants_photo = input("do you want photo ? y or n")
  if wants_photo == "y" :
    bill = bill + 3
  print(f"Your bill is {bill}")
    

else :
  print("you can't come next time")

```

**flow chart improves the understanding where to indent where not to**




### Pizza problem
```python


print("Welcome to Python Pizza Deliveries!")

size = input("What size pizza do you want? S, M, or L ")

add_pepperoni = input("Do you want pepperoni? Y or N ")

extra_cheese = input("Do you want extra cheese? Y or N ")



if size == "S":

  bill = 15

  if add_pepperoni == "Y":

    bill = bill + 2

if size == "M":

  bill = 20

  if add_pepperoni == "Y":

    bill = bill + 3

if size == "L":

  bill = 25

  if add_pepperoni == "Y":

    bill = bill + 3

if extra_cheese == "Y":

  bill = bill+1

print(f"Your final bill is: {bill}")
```
### Logical operator
- to combine different condition generally in **if** statement 

> & and
> | or
> != not

we can also type `and` instead of `&` symbol

```python
print("welcome to the rollercoaster ride")
height = int(input("what is you height"))
if height > 120:
  print("you can ride")
  
  age = int(input("what is your age?"))
  if age < 12:
    bill = 5
    print(f"your bill is {bill}")
  elif age <= 18:
    bill = 7
    print(f"your bill is {bill}")
  elif age>45 & age<55:
    bill = 0
    print("here you go lad free for you")
  else :
    bill = 12
    print(f"your bill is {bill}")
  wants_photo = input("do you want photo ? y or n")
  if wants_photo == "y" :
    bill = bill + 3
  print(f"Your bill is {bill}")
    
else :
  print("you can't come next time")

```

### Love Calculator
### lower case function
```python
name1.lower()
```
### Count function
- it is **case sensitive**
```python
name1.count('a')
```

### Solution

```python

print("Welcome to the Love Calculator!")
name1 = input("What is your name? \n")
name2 = input("What is their name? \n")



t_times = int(name1.lower().count('t'))
r_times = int(name1.lower().count('r'))
u_times = int(name1.lower().count('u'))
e_times = int(name1.lower().count('e'))

t_times1 = int(name2.lower().count('t'))
r_times1 = int(name2.lower().count('r'))
u_times1 = int(name2.lower().count('u'))
e_times1 = int(name2.lower().count('e'))

l_times = int(name1.lower().count('l'))
o_times = int(name1.lower().count('o'))
v_times = int(name1.lower().count('v'))
e_times = int(name1.lower().count('e'))

l_times1 = int(name2.lower().count('l'))
o_times1 = int(name2.lower().count('o'))
v_times1 = int(name2.lower().count('v'))
e_times1 = int(name2.lower().count('e'))

total_t = (t_times + t_times1)
total_r = (r_times + r_times1)
total_e = (e_times + e_times1)
total_u = (u_times + u_times1)

total = total_t + total_r + total_e + total_u

total_l = (l_times + l_times1)
total_o = (o_times + o_times1)
total_v = (v_times + v_times1)
total_e = (e_times + e_times1)

total1 = total_l + total_o + total_v + total_e

love_number = str(total) + str(total1)
print(f"your score is {love_number}")
```

```python
  

print("Welcome to the Love Calculator!")

name1 = input("What is your name? \n")

name2 = input("What is their name? \n")

  
  
  

t_times = int(name1.lower().count('t'))

r_times = int(name1.lower().count('r'))

u_times = int(name1.lower().count('u'))

e_times = int(name1.lower().count('e'))

  

t_times1 = int(name2.lower().count('t'))

r_times1 = int(name2.lower().count('r'))

u_times1 = int(name2.lower().count('u'))

e_times1 = int(name2.lower().count('e'))

  

l_times = int(name1.lower().count('l'))

o_times = int(name1.lower().count('o'))

v_times = int(name1.lower().count('v'))

e_times = int(name1.lower().count('e'))

  

l_times1 = int(name2.lower().count('l'))

o_times1 = int(name2.lower().count('o'))

v_times1 = int(name2.lower().count('v'))

e_times1 = int(name2.lower().count('e'))

  

total_t = (t_times + t_times1)

total_r = (r_times + r_times1)

total_e = (e_times + e_times1)

total_u = (u_times + u_times1)

  

total = total_t + total_r + total_e + total_u

  

total_l = (l_times + l_times1)

total_o = (o_times + o_times1)

total_v = (v_times + v_times1)

total_e = (e_times + e_times1)

  

total1 = total_l + total_o + total_v + total_e

  

love_number = str(total) + str(total1)

  

score = int(love_number)

  

if score < 10 or score > 90 :

 print(f"Your score is {love_number}, you go together like coke and mentos.")

elif score > 40 and score < 50 :

 print(f"Your score is {love_number}, you are alright together")

else :

  print(f"Your score is {love_number}.")
```

### alternate solution
```python

print("Welcome to the Love Calculator!")
name1 = input("What is your name? \n")
name2 = input("What is their name? \n")


combined_names = name1 + name2
lower_names = combined_names.lower()
t = lower_names.count("t")
r = lower_names.count("r")
u = lower_names.count("u")
e = lower_names.count("e")
first_digit = t + r + u + e

l = lower_names.count("l")
o = lower_names.count("o")
v = lower_names.count("v")
e = lower_names.count("e")
second_digit = l + o + v + e

score = int(str(first_digit) + str(second_digit))

if (score < 10) or (score > 90):
  print(f"Your score is {score}, you go together like coke and mentos.")
elif (score >= 40) and (score <= 50):
  print(f"Your score is {score}, you are alright together.")
else:
  print(f"Your score is {score}.")
```


### Day 3 project
## Treasure island
```python
print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.") 

direction = input('You\re at a crossroad. Where do you want to go? Type "left" or "right"').lower()
if direction == "left":
  action = input('You\'ve come to a lake. There is an island in the middle of the lake. Type "wait" to wait for a boat. Type "swim" to swim across.').lower()
  if action == "wait":
    door = input("You arrive at the island unharmed. There is a house with 3 doors. One red, one yellow and one blue. Which colour do you choose?").lower()
    if door == "red":
     print("burned by fire game over")
    elif door == "yellow":
     print("you win")
    elif door == "blue":
     print("eaten by beast game over")
    else :
     print("game over")
      

  else :
    print("attacked by trout, game over")

else:
  print("fall into the game over")
  
```

## Concept
![[Drawing 2022-04-27 19.46.51.excalidraw|3000]]

**we can use `\` to escape it** 
```py
'You\'re at a crossroad. Where do you want to go? Type "left" or "right" '
```

## [ASCII ART](https://ascii.co.uk/art)
for ascii art we use 
```
print(```

```)
```
otherwise it wont print properly

# Day 4 - Beginner - Randomisation and Python Lists
## Random Module
### Randomization
- Games is biggest category
- Python uses *Mersenne Twister* for randomization 
	- Watch video on Khan academy

### randint() function
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

### why random.randint ?
- we are using random module and randint is the function that belongs to random module
- random.random( ) gives value between **0 to 1** only

### Print random decimal in between 1 to 10
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

### Print random decimal in between 1 to 
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

### head or tails programm
```py
import random

random_num = random.randint(0,1)
if (random_num==0):
  print("Heads")
else:
  print("Tails")

```

## Understanding the Offset and Appending Items to Lists
### List
```py
fruit_list = ["apple ", "oranges"]
```

- list can have mixed data type

### Why zero at the beginning ?
![[Understanding the Offset and Appending Items to Lists 2022-05-16 10.58.41.excalidraw|500]]

- since apple is at the beginning, it has *0 offset* and orange is *1 offset* away from beginning
- If we want to print data from last use **negative  sign**

```py
print(states_of_india[-1])
```

### append() to attach at the end of the list

https://docs.python.org/3/tutorial/datastructures.html

The list data type has some more methods. Here are all of the methods of list objects:

```py
list.append(x)
```

Add an item to the end of the list. Equivalent to `a[len(a):] = [x]`.

```py
list.extend(iterable)
```

Extend the list by appending all the items from the iterable. Equivalent to `a[len(a):] = iterable`.

```py
list.insert(i, x)
```

Insert an item at a given position. The first argument is the index of the element before which to insert, so `a.insert(0, x)` inserts at the front of the list, and `a.insert(len(a), x)` is equivalent to `a.append(x)`.

```py
list.remove(x)
```

Remove the first item from the list whose value is equal to _x_. It raises a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError "ValueError") if there is no such item.

```py
list.pop([i])
```

Remove the item at the given position in the list, and return it. If no index is specified, `a.pop()` removes and returns the last item in the list. (The square brackets around the _i_ in the method signature denote that the parameter is optional, not that you should type square brackets at that position. You will see this notation frequently in the Python Library Reference.)

```py
list.clear()
```

Remove all items from the list. Equivalent to `del a[:]`.

```py
list.index(x[, start[, end]])
```

Return zero-based index in the list of the first item whose value is equal to _x_. Raises a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError "ValueError") if there is no such item.

The optional arguments _start_ and _end_ are interpreted as in the slice notation and are used to limit the search to a particular subsequence of the list. The returned index is computed relative to the beginning of the full sequence rather than the _start_ argument.

```py
list.count(x)
```

Return the number of times _x_ appears in the list.

list.sort(_*_, _key=None_, _reverse=False_)

Sort the items of the list in place (the arguments can be used for sort customization, see [`sorted()`](https://docs.python.org/3/library/functions.html#sorted "sorted") for their explanation).

```py
list.reverse()
```

Reverse the elements of the list in place.

```py
list.copy()
```

Return a shallow copy of the list. Equivalent to `a[:]`.

## Banker Roulette - Who will pay the bill
### Using random() concept

```py


import random

names_string = input("Give me everybody's names, separated by a comma. ")
names = names_string.split(", ")

i = random.randint(0,len(names)-1)
print(f"{names[i]} is going to buy the meal today!")

```

### Using choice function 
```py
import random

names_string = input("Give me everybody's names, separated by a comma. ")
names = names_string.split(", ")

random = random.choice(names)
print(f"{random} is going to buy the meal today!")

```

## IndexErrors and Working with Nested Lists
- we can insert/nest two or more list
```py
fruit = ["strawberry", "apples", "oranges"]
vegetable = ["Tomato", "Potato"]
new_combined_list = [fruit, vegetable]
```

## Treasure map exercise
```py
row1 = ["⬜","⬜️","⬜️"]
row2 = ["⬜️","⬜️","⬜️"]
row3 = ["⬜️","⬜️","⬜️"]
map = [row1, row2, row3]
print(f"{row1}\n{row2}\n{row3}")
position = input("Where do you want to put the treasure? ")


hori = int(position[0])
vert = int(position[1])

map[vert-1][hori-1]="X"

print(f"{row1}\n{row2}\n{row3}")
```



# Day 5 - Beginner - Python Loops
## Using loops for python list
### For Loop
```py
fruit_list = ['apple', 'orange', 'banana']

for fruit in fruit_list:
  print(fruit)
```

```py
fruit_list = ['apple', 'orange', 'banana']

for fruit in fruit_list:
  print(fruit)
  print(fruit + " Pie")
```

## Average  height
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
## High Score
```py
list = []

n = int(input("enter the no of student"))

  

for i in range(n):

    x = int(input("enter marks"))

    list.append(x)

  

print(max(list))
```
## for loops and the range() function
### range()
```py
for i in range(1,11):

    print(i)
```

this will print from 1 to *10*

### using steps in range()
```py
for i in range(1,11,3):

    print(i)
```

> 1
> 4
> 7
> 10

### sum of evens only in 1 to 100
```py
sum = 0

for number in range(2,101,2):

    sum = sum + number

print(sum)
```



## Fizzbuzz game
```py
  
for i in range(1,101):

    if i%3==0:

        print("fizz")

    elif i%5==0:

        print("buzz")

    elif i%15==0:

        print("fizzbuzz")

    else:

        print(i)
```
## Password generator
```py
#Password Generator Project
import random
letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']

print("Welcome to the PyPassword Generator!")
nr_letters= int(input("How many letters would you like in your password?\n")) 
nr_symbols = int(input(f"How many symbols would you like?\n"))
nr_numbers = int(input(f"How many numbers would you like?\n"))

password = []
for char in range(1, nr_letters+1):
  password.append(random.choice(letters))
  
for char in range(1, nr_symbols+1):
  password.append(random.choice(symbols))

for char in range(1, nr_numbers+1):
  password.append(random.choice(numbers))

random.shuffle(password)

password_ = ""
for char in password:
  password_+=char
  
print(password_)
```


