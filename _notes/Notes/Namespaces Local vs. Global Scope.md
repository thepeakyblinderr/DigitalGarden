```py
################### Scope ####################

enemies = 1

def increase_enemies():
  enemies = 2
  print(f"enemies inside function: {enemies}")

increase_enemies()
print(f"enemies outside function: {enemies}")
```

local and global scope does not apply only to variable it applies to everything ex -> function( )

```py
def global_function():

  def local_function():

    local_variable = 1

    print(local_variable)

  

  local_function()

  

global_function()

```