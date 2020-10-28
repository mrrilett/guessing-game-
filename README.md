import random
n = random.randint(1, 100)
guess = int(raw_input("Enter an integer from 1 to 100: "))
while n != "guess":
    print
    if guess < n:
        print "guess is low try guessing higher"
        guess = int(raw_input("Enter an integer from 1 to 100: "))
    elif guess > n:
        print "guess is high try guessing lower"
        guess = int(raw_input("Enter an integer from 1 to 100: "))
    else:
        print "you guessed correctly congrats!"
        break
    print
