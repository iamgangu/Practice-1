# Practice-1
##Guess

import random
n=random.randint(0,20)
guess=0;
print("hi, whats your name")
mynmae=input()
print(mynmae+" guess a number")

while (guess!=n):
    guess = int(input())

    if guess >n:
        print("number too large")

    elif guess <n:

        print("too low")

else:

    print('correct')




