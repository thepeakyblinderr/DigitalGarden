if i want to print  Hello World three time I'll have to use print function *three times in three rows* but instead we can use \n

```py
print("hello world\nhello world")
```
 **To run program we can use `Ctrl+Enter`**

# Concatenate
```py
print("hello"+"sandesh")
```
 there won't be any space in between
 output - hellosandesh

```py
print("hello"+" sandesh")
```
now there will be space
OR
```py
print("hello"+" "+"sandesh")
```

**Code intelligence function helps you with Auto complete** 

DeBug name has interesting story behind it

```py
print('print("hello"+" "+"sandesh")')
```

output - print("hello"+" "+"sandesh")
___

```py
print(("New lines can be created with a backslash and n.")
```
this will show parsing error because compiler will think that we are still going to write something because we have incomplete parenthesis

___
```py
print("String Concatenation is done with the "+" sign.")
```

output - String Concatenation is done with the  sign.
here we can see + sign is missing
why ?
because it interpret it as **concatenate**

```py
print('String Concatenation is done with the "+" sign.')
```
 now by changing from " " to ' ' it consider whole thing as one string
 output - String Concatenation is done with the "+" sign