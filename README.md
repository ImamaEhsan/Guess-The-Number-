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
<br>
    UserChoice = int(input("enter the number:"))
<br>
    if(UserChoice == Target):
<br>
        print("Correct Guess!!")
<br>
        break
<br>

    elif(UserChoice < Target):
<br>
        print("take a bigger guess")
<br>

    else:
<br>
        print("your guess was too big,take a smaller one")
    <br>

print("_____GAME OVER______")