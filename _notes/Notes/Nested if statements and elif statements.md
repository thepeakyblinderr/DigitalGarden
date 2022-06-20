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

# elif statement 
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

# BMI 2.0
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
