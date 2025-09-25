# Guess-The-Number-
This is a Repository in which we are creating a game based CODE.
<br>
Author : IMAMA EHSAN

# creating a game code

import random 
<br>
Target = random.randint(1,100)
<br>
while True:
    UserChoice = int(input("enter the number:"))
    if(UserChoice == Target):
        print("Correct Guess!!")
        break

    elif(UserChoice < Target):
        print("take a bigger guess")

    else:
        print("your guess was too big,take a smaller one")

print("_____GAME OVER______")