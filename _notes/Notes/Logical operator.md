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
