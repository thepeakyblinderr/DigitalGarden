```py
import math

height = int(input("enter height"))

width = int(input("enter width"))

  

def can_req(h, w):

  

  amount = (height*width)/5

  amount_r = math.ceil(amount)

  print(f"You'll need {amount_r} cans of paint.")

  

can_req(h=height, w = width)
```

# Math.ceil()
to round off to highest near integer