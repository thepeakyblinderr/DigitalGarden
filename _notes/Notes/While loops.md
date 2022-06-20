- This loop continues till the condition is true
- use **Negation** of sentence to write the condition for *while* loop
- https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Hurdle%201&url=worlds%2Ftutorial_en%2Fhurdle1.json

![[Pasted image 20220528152509.png|400]]

![[Pasted image 20220528153213.png|400]]

```py
def turn_right():
    turn_left()
    turn_left()
    turn_left()
    
def draw_square():
    turn_left()
    move()
    turn_right()
    move()
    turn_right()
    move()
    turn_right()
    move()

def jump():
    move()
    turn_left()
    move()
    turn_right() 
    move()
    turn_right()
    move()
    turn_left()
    
number_of_hurdles = 6
while number_of_hurdles > 0:
    jump()
    number_of_hurdles -= 1
    
```

# Infinite Loop
![[Pasted image 20220528155304.png|300]]

```py
while 5>3:
    print(5>3)
```
it will always print **True** 

