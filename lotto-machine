import random

def lotto():
    """With lotto() you can try your luck and win amazing prices..."""

    def choice():
        '''Play again or go home'''
        choice = input("Continue? (y/n) \n")
        if choice == 'y' or choice == 'Y':
            lotto()
        else:
            print("Goodbye!")
            return

    lucky_num = random.randint(1, 10)
    my_num = input("Please place your bet, enter a number between 1 and 10:\n")

    if int(my_num) not in range(1,11):
        print("That's not a valid number, try again!\n")
        lotto()
    else:
        print("You chose the number " +str(my_num)+".")
        print("Our lucky number is " +str(lucky_num)+"!")

        if int(my_num) == lucky_num:
            print("You Win!")
            choice()
        else:
            print("Sorry...Please try again..")
            choice()

lotto()
