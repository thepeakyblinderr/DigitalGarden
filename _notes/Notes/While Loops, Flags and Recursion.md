```py
#Calculator
def add(n1, n2):
  return n1 + n2

def subtract(n1, n2):
  return n1 - n2

def multiply(n1, n2):
  return n1 * n2

def divide(n1, n2):
  return n1 / n2

operations = {
  "+": add,
  "-": subtract,
  "*": multiply,
  "/": divide
}

num1 = int(input("What's the first number?: "))
for symbol in operations:
  print(symbol)

should_continue = True
while should_continue:
  #Here we select "+"
  operation_symbol = input("Pick an operation: ") 
  num2 = int(input("What's the next number?: "))
  calculation_function = operations[operation_symbol]
  answer = calculation_function(num1, num2)
  
  print(f"{num1} {operation_symbol} {num2} = {answer}")
  if input(f"type yes to continue with {answer} and no to exit") == 'yes':
    num1 = answer 
  else:
    should_continue = False
```

# Recursion
function calls itself

```py
#Calculator
def add(n1, n2):
  return n1 + n2

def subtract(n1, n2):
  return n1 - n2

def multiply(n1, n2):
  return n1 * n2

def divide(n1, n2):
  return n1 / n2

operations = {
  "+": add,
  "-": subtract,
  "*": multiply,
  "/": divide
}
def calculator():
  num1 = int(input("What's the first number?: "))
  for symbol in operations:
    print(symbol)
  
  should_continue = True
  while should_continue:
    #Here we select "+"
    operation_symbol = input("Pick an operation: ") 
    num2 = int(input("What's the next number?: "))
    calculation_function = operations[operation_symbol]
    answer = calculation_function(num1, num2)
    
    print(f"{num1} {operation_symbol} {num2} = {answer}")
    if input(f"type yes to continue with {answer} and no to exit or start again") == 'yes':
      num1 = answer 
    else:
      should_continue = False
      calculator()


calculator()
```
