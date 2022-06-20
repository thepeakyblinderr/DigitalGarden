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

when it has zeroes at the end check divisibility by
400
ex - 1700 is not leap year