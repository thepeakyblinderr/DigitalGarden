![[Pasted image 20220607153138.png]]
- Return means that line of code will be replaced by output and later on we can save it in variable called output

![[Pasted image 20220607153145.png]]

```py
def format_name(f_name, l_name):
  print(f_name.title())
  print(l_name.title())

format_name("anGela", "sandesH")

```
![[Pasted image 20220607154150.png]]
___
```py
def format_name(f_name, l_name):
  f_f = f_name.title()
  f_l = l_name.title()
  print(f"{f_f} {f_l}")

format_name("sandesh", "WANKHADE")
```
![[Pasted image 20220607154813.png]]
___
## Return
```py
def format_name(f_name, l_name):
  f_f = f_name.title()
  f_l = l_name.title()
  return (f"{f_f} {f_l}")

format_name("sandesh", "WANKHADE")
```
this wont give output 
because format_name("sandesh", "WANKHADE") is replaced by output but we havent print it
so we need to use another variable to save the **return** value