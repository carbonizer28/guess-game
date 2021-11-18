import sys
from random import randint
from sys import argv
answer = randint(1,10)



while True:
    try:
        guess = int(input("please guess a number between 1 and 10: "))
        if 0 < guess < 11:
            print(answer)
            if guess == answer:
                print("Congrats!")
                break
        else:
            print("Please use a number within the range provided")
    except ValueError:
        print("Please use a number")
        continue
sys.argv[0]
sys.argv[1]
#generate a number  1~10
# input from the user
# check that input is a number 1~10
# check if number is the right guess, otherwise ask again

