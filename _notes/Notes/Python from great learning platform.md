
---
time: 09:57
date: 2022-04-07 
tag: programming python                
---
```toc
```

# 1. Python from great learning paltform


# 2. Importance and Applications of Programming Languages
grammatical rules for language = syntax in programming

# 3. Variables in Programming
we need **variable** to store **data** temporarily 
variables has address 

# 4. Decision Making Statements
When condition is involved
![[Pasted image 20220407095625.png|300]]

# 5. Looping Statements
To repeat the task
*Ex - keep playing song until the app is closed*
![[Pasted image 20220407100132.png|300]]

# 6. Functions in Programming
Eating , Running are our function
**Function** :
	A code block which perform specific task
	A readymade code
# 7. Object Oriented Programming Concepts
Phone, Laptop and bags are **object**s around me
**Class** - blueprint for real world entities
**objects** have *properties* and *behavior*
![[Pasted image 20220407100723.png|300]]

![[Pasted image 20220407100750.png|300]]
- Here class is Mobile phone and apple , motorola and samsung is object
- Since these are part of **same class** they would have same *properties* and *behavior*
- But they will have different values 
	- Here color of all mobiles might be different
	- May be the same button has different function in different phone
# 8. Algorithmic Approach to Solve a Problem
![[Pasted image 20220407101829.png|300]]
**Algorithm** :
	step by step approach
# 9. Intro to Python
- It has Large library
- IDE is integrated development environment
- **PyCharm** - IDE
- **Anaconda** - Web based distribution 
	- for data science 
	- data science packages/library
	- tensor flow
	- data visualization
	- **Anaconda Prompt** --> jupyter notebook
	- **Anaconda Navigator**
- **Jupyter** **Notebook**
	-   .ipnyb files
# 10. Variables and Data-types in Python

![[Pasted image 20220407111547.png]]

# 11. Operators in Python
- Arithmetic Operators
	- {  + - * / }
- Relational Operators
	- {> < ==}
- Logical Operators

![[Pasted image 20220408111323.png]]
- ***&*** ,if both are true then only true
- ***|*** , even if one is true output will be true symbol is known as Pipe

# 12. Tokens in Python
![[Pasted image 20220408111905.png]]

![[Pasted image 20220408111926.png]]
we cannot have variables named same as keyword
in jupyter notebook keyword are *green
___


![[Pasted image 20220408112057.png]]

# 13. Strings in Python
* single quotes or double or triple it doesn't matter
*[[Python from Harry#String]]*

## To extract last character

```
my_name = "sandesh wankhade"
my_name[-1]
```
![[Pasted image 20220410104423.png]]
## To find number of occurrence 
![[Pasted image 20220410105828.png]]
## Finding the index of substring
```
s1 = "this is sparta"
s1.find("sparta")
```

## Splitting the string
```
my_name = 'sandesh,samartha,wankhade'
my_name.split(',')

['sandesh', 'samartha', 'wankhade']
```

# 14. Python Tuples

[[Python from Harry#Tuple]]

collection of heterogenous elements

## Repeating tuple elements
```
tup1 = (2,"sandesh",True)
tup1*3

(2, 'sandesh', True, 2, 'sandesh', True, 2, 'sandesh', True)
```
##  Repeating and Concatenating

```
tup1 = (2,"sandesh",True)
tup2 = (300,"wankhade")
tup1*2+tup2

(2, 'sandesh', True, 2, 'sandesh', True, 300, 'wankhade')
```

## Max and Min of tuple
```
tup3 = (1,2,3,4,5,6)
min(tup3)

1
```

# 15.List in Python

- list are mutable(can be changed)
	- are defined within [  ]
	- while tuple within ( )
[[Python from Harry#List function]]

## Reversing the list
![[Pasted image 20220410113523.png|400]]

## Sorting list
![[Pasted image 20220410113557.png|400]]

- Repeat and concatenate same as **Tuple** 
	-  [[Python from great learning platform#Repeating tuple elements]]

# 16. Dictionary in Python

- It is unordered collection
- Written in { }
- key value pairs inside { }
	- ![[Pasted image 20220410115022.png]]

## Extract keys
![[Pasted image 20220410115301.png]]

## Extracting Values 
![[Pasted image 20220410115329.png]]

## Extract Items
![[Pasted image 20220410115649.png]]

## Adding a new element
![[Pasted image 20220410115812.png]]

## Changing an existing element
![[Pasted image 20220410115839.png]]


## Update one dictionary with another
![[Pasted image 20220410120435.png]]

## Popping an element
![[Pasted image 20220410120502.png]]

# 17. Set in Python

- Unordered and unindexed (can't access individual element)
- Duplicate are not allowed
- ![[Pasted image 20220410120838.png]]
- Written in { }
- ![[Pasted image 20220410120945.png|10000]]
- ![[Pasted image 20220410121247.png]]