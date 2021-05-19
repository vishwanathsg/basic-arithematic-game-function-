# basic-arithematic-game-function-
This is a basic arithmatic game, having a function with calculations

#Function_Arithmatic : Input some numbers, do some simple arithmetic, output results
#Arrange these three integers (2,3 & 4) such that, the resultant number is the highest of all the combinations
#(X) x (Y) / (Z) - It'll be performed directly from left to right
#NOTE:This game does not appreciate decimal number inputs
#But still if the user types a number like 2.0, it still counts as 2, that's why I used float)

def compute(x,y,z):
 P=x*y//z
 return P

"""
Input : x,y & z are positive numbers 
Returns True if x, y & z are positive, negative numbers, otherwise False
"""

X=float(input("Enter value for X: "))
Y=float(input("Enter value for Y: "))
Z=float(input("Enter value for Z: "))
result=compute(X,Y,Z)


if result < 6:
 print("try again, this is not the correct order")

else :
 print("there are two correct combinations, and this is one them! good job!")
