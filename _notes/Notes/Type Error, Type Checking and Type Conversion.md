# Type error
We cannot **concatenate** string with number

```py
num_char = len(input("what is your name?"))
print("Your name has " + num_char + "characters")
```

will show error

# Type checking
type() function to check data type

```py
num_char = len(input("what is your name?"))
# print("Your name has " + num_char + "characters")
print(type(num_char))
```

`what is your name?adesh`
`<class 'int'>`

---
# Type casting
```py
num_char = len(input("what is your name?"))

new_num_char = str(num_char)

print("Your name has " + new_num_char + " characters")

```

`what is your name?sandesh`
`Your name has 7 characters`

here it is converted from INT to STRING
___

# Concepts

```py
print(70 + float("100.5"))
```

`170.5`
here string is converted into float and then added 

```py
print(str(70)+str(110))
```

`70110`
___
# Example
## Write a program that adds the digits in a 2 digit number. e.g. if the input was 35, then the output should be 3 + 5 = 8

```py


two_digit_number = input("Type a two digit number: ")



str(two_digit_number)

a = two_digit_number[0]

b = two_digit_number[1]

  

new_a = int(a)

new_b = int(b)

  

print(new_a + new_b)
```

