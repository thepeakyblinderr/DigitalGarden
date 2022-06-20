![[Pasted image 20220620141135.png]]


- each starting letter of word should be capital
	- known as pascal case

![[Pasted image 20220620142301.png]]
- We can fetch variables from another module and use it in main.py
- same can be done with class

```py
import turtle  
  
from turtle import Turtle  
  
timmy = Turtle()  # new object has been created

```

##  Object.attributes 
- car.speed


```py
import turtle  
  
from turtle import Turtle, Screen  
  
timmy = Turtle()  # new object has been created  
print(timmy)  
  
screen_size = Screen()  
print(screen_size.canvheight)
```
- screen_size is object and canvheight is attribute

## Object methods
![[Pasted image 20220620144939.png]]

```py
import turtle  
  
from turtle import Turtle, Screen  
  
timmy = Turtle()  # new object has been created  
print(timmy)  
timmy.shape("turtle")  
  
screen_size = Screen()  
print(screen_size.canvheight)  
  
screen_size.exitonclick()
```

![[Pasted image 20220620145332.png]]

## Turtle documentation
https://docs.python.org/3/library/turtle.html