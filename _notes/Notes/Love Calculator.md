# lower case function
```python
name1.lower()
```
# Count function
- it is **case sensitive**
```python
name1.count('a')
```

# Solution

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

## alternate solution
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

