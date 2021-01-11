the_word = "Yes"
guess = ""
guess_count = 0
guess_limit = 2
out = False

while  guess != the_word and not out:
    if guess_count < guess_limit:
        guess =input (" Add your answer ")
        guess_count+=1
    else:
        out = True
if out:
    print("you  lose")
else:
    print("You win")
