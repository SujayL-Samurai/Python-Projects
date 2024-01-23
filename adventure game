name = input("Type your name: ")
print("Welcome", name, "to this adventure!!")

answer = input("You are on a dirt road, it has come to an end and you can go left or right. Which way would like to go?: ").lower()

if answer == "left":
    answer = input("You come to river, you can walk around it or swim to swim across?(walk or swim): ")
    if answer == "swim":
        print("You swam across and were eaten by an alligator! :(")
    elif answer == "walk":
        print("You walked for many miles, ran out of water and you lost the game! :(")

elif answer == "right":
    answer = input("You come to a bridge, it looks wobbly, do you want to (head back or cross)?: ")

    if answer == "head back":
        print("You go back and lose! :(")
    elif answer == "cross":
        answer = input("You crossed the bridge and meet a stranger. Do you want to talk to them(yes or nor)?: ")

        if answer == "yes":
            print("You talked to the stranger. You got the gold from the stranger. You win! :)" )
        if answer == "no":
            print("You ignored the stranger and they are offended. You lose! :(")
else:
    print("Not a valid option. You lose! :(")

print("Thank you for trying!", name)
