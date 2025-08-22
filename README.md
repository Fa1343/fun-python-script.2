# guess_number.py
import random

secret = random.randint(1, 20)
print("🎯 Guess the number between 1 and 20!

while True:
    guess = int(input("Your guess: "))
    if guess < secret:
        print("Too low!")
    elif guess > secret:
        print("Too high!")
    else:
        print(f"✅ Correct! The number was {secret}.")
        break# fun-python-script.2
just for fun
