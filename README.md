#                        Treasure island game

z=("Welcome to the treasure hunt")
uc=z.upper()
print(uc)
 
a=input("Please Enter the name of the player: ")
print(f"Welcome to the queast sir {a}")

b=int(input("Please enter your age"))
if(b >= 18):
    print("you are elegibal for the game.")
    print("In this game you will be asked several question and based on the answer you will move ahead or die")
    c=input("You are at the cross road where you want to go left(l) ot right(r): ")
    if( c == 'r'):
        print("When you move further you find a lake and treasure on opposite the what will choose")
        d=input("Wait for the boat(b) or swim through the river(s)")
        if(d == 'b'):
            print("Now you have entered in the castel ")
            e=input("There are 3 doors choose one. Red(r), Blue(b),Yellow(y): ")
            if(e == 'r'):
                print("there is a fire you lost")
            elif(e == 'b'):
                print("This room has sharks you lost")
            else:
                print("Yaah!! you found the treasure...........")
        else:
            print("You have been eaten by sharks........")
    else:
        print("congratulations!! Yoh have choosen the easiest root....")
        print("When you move futher there is a castel")
        e=input("There are 3 doors choose one. Red(r), Blue(b),Yellow(y): ")
        if(e == 'r'):
            print("there is a fire you lost")
        elif(e == 'b'):
            print("This room has sharks you lost")
        else:
            print("Yaah!! you found the treasure...........")

x=("The game ends thanks for playing")
uc2= x.upper()
print(uc2)
