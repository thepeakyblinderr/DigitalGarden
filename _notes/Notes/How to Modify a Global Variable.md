usually a bad idea to have both local and global variables same name

![[Pasted image 20220614134640.png]]

this will show error as enemies is local and since it is not defined first we cant modify it
it should be defined inside the function first`

		-Traceback (most recent call last):
		  File "main.py", line 9, in <module>
		    increase_enemies()
		  File "main.py", line 6, in increase_enemies
		    enemies += 1
		  UnboundLocalError: local variable 'enemies' referenced before assignment


This is correct
```py
################### Scope ####################

enemies = 1

def increase_enemies():
  enemies = 3
  enemies += 1
  print(f"enemies inside function: {enemies}")

increase_enemies()
print(f"enemies outside function: {enemies}")
```

but here it is changing the local variable within the function

# if i want to change the global variable ?
good practice to avoid modifying global variable

```py
################### Scope ####################

enemies = 3

def increase_enemies():
  global enemies 
  enemies += 1
  print(f"enemies inside function: {enemies}")

increase_enemies()
print(f"enemies outside function: {enemies}")
```

		enemies inside function: 4
		enemies outside function: 4
