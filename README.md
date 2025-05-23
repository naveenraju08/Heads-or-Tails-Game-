 # Heads or Tails !


    # Heads or Tails !
import random

while True:
     
    x = input("Wanna play the game(Y/N)?: ").lower()
    y = "Heads" , "Tails"
    i = 1

    if x =="y":    
        print("".join(random.choice(y)))
        i +=1
        
    elif x =="n":
            print("Try once Manhh!")
            break
    else:
        print("Invalid! Enter in (Y/N)")    
