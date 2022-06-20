```py
#Step 3

import random
word_list = ["aardvark", "baboon", "camel"]
chosen_word = random.choice(word_list)
word_length = len(chosen_word)

#Testing code
print(f'Pssst, the solution is {chosen_word}.')

#Create blanks
display = []
for _ in range(word_length):
    display += "_"

#TODO-1: - Use a while loop to let the user guess again. The loop should only stop once the user has guessed all the letters in the chosen_word and 'display' has no more blanks ("_"). Then you can tell the user they've won.
end_of_game = False

while not end_of_game:
    guess = input("Guess a letter: ").lower()

    #Check guessed letter
    for position in range(word_length):
        letter = chosen_word[position]
        #print(f"Current position: {position}\n Current letter: {letter}\n Guessed letter: {guess}")
        if letter == guess:
            display[position] = letter

    print(display)

    #Check if there are no more "_" left in 'display'. Then all letters have been guessed.
    if "_" not in display:
        end_of_game = True
        print("You win.")
```

OR

```py
# hangman game

  

import random

stages = ['''

  +---+

  |   |

  O   |

 /|\  |

 / \  |

      |

=========

''', '''

  +---+

  |   |

  O   |

 /|\  |

 /    |

      |

=========

''', '''

  +---+

  |   |

  O   |

 /|\  |

      |

      |

=========

''', '''

  +---+

  |   |

  O   |

 /|   |

      |

      |

=========''', '''

  +---+

  |   |

  O   |

  |   |

      |

      |

=========

''', '''

  +---+

  |   |

  O   |

      |

      |

      |

=========

''', '''

  +---+

  |   |

      |

      |

      |

      |

=========

''']

from turtle import pos, position

# step 1 - i need words

word_list = ["anaconda", "baboon", "sandesh"]

  

# step 2 - gnerate a random words but user shouldnt be able to see it , so replace those with blanks

chosen_word = random.choice(word_list)

  

print(chosen_word) # should not appear we are just testing

# step 3 - replace all the letters in word with blanks

# for that we need list

display = []

for letters in range(len(chosen_word)):

  display += "_"

  

print(display)

end_of_game = False

lives = 6

  

# step 4 - take input from user, use lower function

while not end_of_game:

  guess = input("enter your guess").lower()

  

# step 5 - check input from user matches letter in word, if matches display that letter in that position

  for position in range(len(chosen_word)):

    if chosen_word[position] == guess:

      display[position] = guess

  print(display)

  if guess not in chosen_word:

    lives-=1

    if lives==0:

      end_of_game = True

      print("endgame")

# this should continue till all the blamks are filled with letters

# means logic there shoul not be blank

# if no blank then end of game

  if "_" not in display:

    end_of_game = True

    print("win")

  

  print(stages[lives])
```