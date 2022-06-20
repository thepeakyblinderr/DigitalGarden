- here there are multiple **if** which check each condition it is false then it moves onto the next **if** statement
```python
if cond a:
 do a
if cond b:
 do b
if cond c:
 do c
```

# Roller-coaster program
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


