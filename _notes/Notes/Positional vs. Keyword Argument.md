# Functions with more than one input

## **Positional Argument**
```py
def name_and_location(name, location):
  print(f"hi {name}")
  print(f"what is it like to be in {location}")

name_and_location("sandesh", "Mumbai")
```

- This is default way of calling a function known as **Positional Argument**

## **Keyword Argument**
![[Pasted image 20220604135156.png|300]]

![[Pasted image 20220604135206.png|300]]

- Both will have same output even though we change the order around
```py
def name_and_location(name, location):
  print(f"hi {name}")
  print(f"what is it like to be in {location}")

name_and_location(location = "Mumbai", name = "sandesh wankhade")
```
