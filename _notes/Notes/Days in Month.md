```py
def is_leap(year):
  if year % 4 == 0:
    if year % 100 == 0:
      if year % 400 == 0:
        return True
      else:
        return False
    else:
      return True
  else:
    return False

def days_in_month(year_, month_):
  month_days = [31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31]  
  if month_ <1 or month>12:
    return
  
  if is_leap(year_)  and month == 2:
    return  29
  else:
    return month_days[month_-1]
  
  
#🚨 Do NOT change any of the code below 
year = int(input("Enter a year: "))
month = int(input("Enter a month: "))
days = days_in_month(year, month)
print(days)

```

NOTE - if is_leap() in this statement is_leap() == true then automatically if statement will be excuted