from random import randint
import sys
answer = randint(int(sys.argv[1]), int(sys.argv[2]))
interaction = int(sys.argv[1]), int(sys.argv[2])

while True:
    try:
        guess = int(input(f"please guess a number between {interaction}: "))
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
#generate a number  1~10
# input from the user
# check that input is a number 1~10
# check if number is the right guess, otherwise ask again

