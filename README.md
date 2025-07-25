# python-diceroll
print("Roll a dice (y/n)")
response= input().lower()
if response == 'y':
    import random
    print("You rolled a", random.randint(1, 6))
else:
    print("Thanks for playing!")
