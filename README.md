while True:
    print("Roll a dice (y/n)")
    response= input().lower()
    if response == 'y':
        import random
        print("You rolled a", random.randint(1, 6))
    elif response !='n' and response != 'y':
        print("Invalid input, please enter 'y' or 'n'.")
    else:
        print("Thanks for playing!")
        break
