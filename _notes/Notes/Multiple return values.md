```py
def format_name(f_name, l_name):
  f_f = f_name.title()
  f_l = l_name.title()
  return (f"{f_f} {f_l}")
  print("i am stupid")

output = format_name("sandesh", "WANKHADE")
print(output)
```

it doesn't print the statement ,  print("i am stupid")
because return is the end of function

```py
def format_name(f_name, l_name):
  f_f = f_name.title()
  f_l = l_name.title()
  return (f"{f_f} {f_l}")
  

output = format_name(input("enter your first name"), input("enter your last name"))
print(output)
```
![[Pasted image 20220607160535.png]]
if we don't give any input , it will go through al the code till return statement
but if we want to bypass it then following can be done
```py
def format_name(f_name, l_name):
  if f_name == "" or l_name == "":
    return
  f_f = f_name.title()
  f_l = l_name.title()
  return (f"{f_f} {f_l}")
  

output = format_name(input("enter your first name"), input("enter your last name"))
print(output)
```
![[Pasted image 20220607160832.png]]

