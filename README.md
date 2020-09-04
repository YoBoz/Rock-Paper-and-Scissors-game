# Rock-Paper-and-Scissors-game
#A simple Python game.
import random
print("Welcome to Rock,Paper,Scissor Game!!!!")
print()
a=input("Please Enter Your Name:")
print()
print("Hello",a,",")
b=['paper','rock','scissor']
e='y'
while e=='y':
c=random.choice(b)
d=input("Enter Rock, Paper or Scissor:")
print()
if c=="paper" and d=="rock":
print("Computer used,",c)
print("You Lost",a,"!!!","Try Again")
elif c=="paper" and d=="scissor" :
print("Computer used,",c)
print("Congratulations",a,"","You Won:-)")
elif c=="paper" and d=="paper" :
print("Try Again,Both played same move")
elif c=="rock" and d=="paper":
print("Computer used,",c)
print("Congratulations",a,"","You Won:-)")
elif c=="rock" and d=="scissor" :
print("Computer used,",c)
print("You Lost",a,"!!!","Try Again")
elif c=="rock" and d=="rock" :
print("Try Again,Both played same move")
elif c=="scissor" and d=="rock":
print("Computer used,",c)
print("Congratulations",a,"","You Won:-)")
elif c=="scissor" and d=="paper" :
print("Computer used,",c)
print("You Lost",a,"!!!","Try Again")
elif c=="scissor" and d=="scissor" :
print("Try Again,Both played same move")
else:
print("Invalid Option!!!")
break
e=input("Do you want to continue [y/n]?:")
else:
print("Thank-You",a,"for playing this game!!!")
