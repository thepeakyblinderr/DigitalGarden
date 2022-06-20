- if you create a variable within the function then that variable is available within the function
```py
game_level = 3

enemies = ["spider", "lion", "elephant"]
  
if game_level < 5:

  new_enemy = enemies[2]
 
print(new_enemy)
```

This is valid code , there is no global or local in codeblocks its in function()

> Remember that in Python there is no block scope. Inside a if/else/for/while code block is the same as outside it.