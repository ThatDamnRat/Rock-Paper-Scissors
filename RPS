### Rock, Paper, Scissors ####

from random import randint


def welcome():
    print()
    print('~ Rock, Paper, Scissors ~ ')
    print()
def RPS():
    # Varianbles set up
    hands = ['rock', 'paper', 'scissors']
    npc = hands[randint(0, 2)]
    pc = str(input('What will you use? (rock, paper, scissors) '))
    # Draw conditional
    if npc == pc:
        print()
        print('Computer: ' + npc + ' Vs. You: ' + pc)
        print('Draw...')
        print()
    # Player chooses rock
    elif pc == 'rock':
        if npc == 'paper':
            print()
            print('Computer: ' + npc + ' Vs. You: ' + pc)
            print('Paper covers rock, you lose')
            print()
        if npc == 'scissors':
            print()
            print('Computer: ' + npc + ' Vs. You: ' + pc)
            print('Rock crushes scissors, you win')
            print()
    # Player chooses paper
    elif pc == 'paper':
        if npc == 'scissors':
            print()
            print('Computer: ' + npc + ' Vs. You: ' + pc)
            print('Scissors cut paper, you lose')
            print()
        if npc == 'rock':
            print()
            print('Computer: ' + npc + ' Vs. You: ' + pc)
            print('Paper covers rock, you win')
            print()
    # player chooses Scissors
    elif pc == 'scissors':
        if npc == 'rock':
            print()
            print('Computer: ' + npc + ' Vs. You: ' + pc)
            print('Rock crushes Scissors, you lose')
            print()
        if npc == 'paper':
            print()
            print('Computer: ' + npc + ' Vs. You: ' + pc)
            print('Scissors cut paper, you win')
            print()
    else:
        print("You must enter either: 'rock', 'paper', or 'scissors'")
        print()

welcome()
try:
    while True:
        RPS()
except ValueError:
    print("You must enter either: 'rock', 'paper', or 'scissors'")