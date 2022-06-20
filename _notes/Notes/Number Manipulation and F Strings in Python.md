# Rounding of number
if number is 2.5 then round off to 3
to do that `round()` function

```py
print(round(8/3))
```

`3`

## Number of places you want to round it to
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

# F string
if there are different data types , it is painful to convert one data into another and use `+` sign every time , to avoid that we use **f- string**
```py
score = 0
height = 1.8
isWinning = True

print(f"your score is {score},your height is {height}, are you winning son {isWinning}")
```
`your score is 0,your height is 1.8, are you winning son True`

# Create a program using maths and f-Strings that tells us how many days, weeks, months we have left if we live until 90 years old

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
