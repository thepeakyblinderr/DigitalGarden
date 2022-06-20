```py
from art import logo
print(logo)

def add(n1,n2):
  return n1+n2

def subtract (n3,n4):
  return n3-n4

def multiply(n5,n6):
  return n5*n6

def divide(n7,n8):
  return n7/n8

operation = {
  "+" : add,
  "-" : subtract,
  "*" : multiply,
  "/" : divide,
            
}

function = operation["+"]
function(num1, num2)
# function will be assigned add
# then function(num1, num2) is nothing but add(num1, num2)

num1 = int(input("What is your first number ?: "))
num2 = int(input("What is your second number ?: "))
```