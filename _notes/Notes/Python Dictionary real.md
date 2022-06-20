- similar to dictionary in real life
![[Pasted image 20220606140935.png]]

- key --> word in dictionary
- Value --> meaning of word

![[Pasted image 20220606141140.png]]

![[Pasted image 20220606141155.png]]

![[Pasted image 20220606141221.png]]


```py
programming_dictionary = {
	"Bug": "An error in a program that prevents the program from 
    running as expected.", 
	"Function": "A piece of code that you can easily call over and 
    over again."
}
```
- **This exact formatting should be followed**

This acts similar to list[]

```py
programming_dictionary = {
  "Bug": "An error in a program that prevents the program from running as expected.", 
  "Function": "A piece of code that you can easily call over and over again."
}

print(programming_dictionary["Bug"])
```

- we can add new **key** to dictionary
```py
programming_dictionary = {
  "Bug": "An error in a program that prevents the program from running as expected.", 
  "Function": "A piece of code that you can easily call over and over again."
}

print(programming_dictionary["Bug"])

programming_dictionary["loop"] = "the action  of doing something over and over again"

print(programming_dictionary)

```

**Empty dictionary**
```py
empty_dictionary = {}
```

**we can empty dictionary**
```py
empty_dictionary = {}
```

**Edit  an item in dictionary**
```py
programming_dictionary = {
"Bug": "An error in a program that prevents the program from running as expected.", 
"Function": "A piece of code that you can easily call over and over again."
}



programming_dictionary["loop"] = "the action  of doing something over and over again"


programming_dictionary["Bug"] = "a moth in computer"

print(programming_dictionary["Bug"])


```

**Loop through  a dictionary**
```py
for key in programming_dictionary:
  print(key)
  print(programming_dictionary[key])
```