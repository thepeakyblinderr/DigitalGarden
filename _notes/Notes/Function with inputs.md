![[Pasted image 20220604132212.png|500]]

# Defining a function
```py
def greet():
  print("hello world")


for n in range(0,10):
  greet()
```

# Function with inputs
![[Pasted image 20220604132839.png]]

- this *Something* variable sis passed to the  function
- While calling function let us say we pass 
```py
my_function(123)

```

this 123 is passed to the something and repalces *something* in the **definition code**

```py
def greet_with_name(name):
  print(f"hello {name}")

greet_with_name("sandesh")
```

- here name is **parameter** 
- and sandesh is  **argument**
