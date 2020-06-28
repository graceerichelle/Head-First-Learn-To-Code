import random

winner = ''

random_choice = random.randint(0,2)

if random_choice == 0:
    computer_choice = 'rock'
elif random_choice == 1:
    computer_choice = 'paper'
else:
    computer_choice = 'scissors'

user_choice = 'scissors'
while (user_choice != 'rock' and
       user_choice != 'paper' and
       user_choice != 'scissors' ):
    user_choice = input('rock, paper, or scissors? ')
if computer_choice == user_choice:
    winner = 'tie'
elif computer_choice == 'paper' and user_choice == 'rock':
    winner = 'computer'
elif computer_choice == 'rock' and user_choice == 'scissors':
    winner = 'computer'
elif computer_choice == 'scissors' and user_choice == 'paper':
    winner = 'computer'

else:
    winner = 'user'

if winner == 'tie':
    print('We both chose', computer_choice + ', play again')
else:
    print(winner, 'won, the computer chose', computer_choice + '.')
