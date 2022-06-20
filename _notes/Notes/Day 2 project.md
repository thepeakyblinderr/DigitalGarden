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
