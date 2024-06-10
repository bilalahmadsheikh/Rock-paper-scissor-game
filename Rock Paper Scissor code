#rock paper scissor
import random
def gameplay(c1,u1):
    if u1=="r":
        u1="rock"
    elif u1=="p":
        u1="paper"
    else:
        u1="scissor"
    if c1==u1:
        print("it is a tie")
    elif c1=="rock":
        if u1=="scissor":
            print("you lost")
        else:
            print("you won")
    elif c1=="paper":
        if u1=="scissor":
            print("you won")
        else:
            print("you lost")
    else:
        if u1=="rock":
            print("you won")
        else:
            print("you lost")                          
c=random.randint(1,3)
if c==1:
    c="rock"
elif c==2:
    c="paper"
else:
    c="scissor"
for i in range(1,5):        
    u=input("Select rock(r) paper(p) scissor(s)")
    if u=="r" or u=="p" or u=="s":
        gameplay(c,u)
        print("Computer selected",c)
        break
    else:
        print("invalid entry")
