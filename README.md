# Python-project-1
Game of Rock paper&amp; scissors 
import random
user_choice=int(input("enter the numbers: ('0'for Rock)('1'for paper)('2'for sissors)"))
if user_choice>2 or user_choice<0 :
    print("invalid input 'you loose the game'")
else :
    computer_choice=random.randint(0,2)
    print(computer_choice)
    if user_choice==computer_choice :
        print("it's a draw")
    elif user_choice == 0 and computer_choice == 2 :
        print("you won the game")
    elif user_choice == 2 and computer_choice == 0 :
        print("your loose the game")
    elif computer_choice > user_choice :
        print("you loose the game")
    elif computer_choice < user_choice :
        print("you won the game")
