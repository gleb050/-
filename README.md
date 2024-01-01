import sys
from colorama import init
from colorama import Fore, Back, Style
init()
import random
print(Fore.GREEN)

balance = 100
print("__________________________________________")
print ("balance: "+str(balance))
stavca = input("How much are we betting on?: ")
b = input()
a = random.randint(0,5)
if int(b) == a:
    print("win")
    balance1 = int(balance) + int(stavca)
    
    
else:
    print("no")
    balance1 = int(balance) - int(stavca)
if balance1 == 0 or balance1 < 0:
    print("game over")
    sys.exit()
    
print("it was: "+str(a))

print("__________________________________________")

b = input()
a = random.randint(0,5)
if int(b) == a:
    print("win")
    balance12 = int(balance1) + int(stavca)
else:
    print("no")
    balance12 = int(balance1) - int(stavca)
print("it was: "+str(a))
if balance1 == 0 or balance1 < 0:
    print("game over")
    sys.exit()
print("__________________________________________")

b = input()
a = random.randint(0,5)
if int(b) == a:
    print("win")
    balance123 = int(balance12) + int(stavca)
else:
    print("no")
    balance123 = int(balance12) - int(stavca)
print("it was: "+str(a))
print (balance123)
if balance1 == 0 or balance1 < 0:
    print("game over")
    sys.exit()
print("__________________________________________")
input ()  
