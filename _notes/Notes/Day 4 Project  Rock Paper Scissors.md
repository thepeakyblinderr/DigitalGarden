```py
import random
rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

#Write your code below this line 👇

choice = int(input("enter your choice"))
if choice==0:
  print(rock)
elif choice==1:
  print(paper)
else:
  print(scissors)

comp_random = random.randint(0,2)
if comp_random == 0:
  print(rock)
elif comp_random == 1:
  print(paper)
else:
  print(scissors)

if comp_random == choice:
  print("tie")
elif comp_random == 0 and choice == 2:
  print("comp wins")
elif comp_random == 1 and choice == 0:
  print("comp wins")
elif comp_random == 2 and choice == 1:
  print("comp wins")
else:
  print("you  win")
```

