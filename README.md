# Rock-Paper-Scissor



timing = input("Do you you want to shoot on 1,  2, or 3.....")
    
if timing == "1":
    choice = input("Choose Rock, Paper, Scissor..........")

    if choice == "rock":
        print("Your opponet choose Paper")
        print("You lost")
    
    elif choice == "paper":
        print("Your opponent choose Scissor")
        print("You lost")
    
    
    elif choice == "Scissor":
        print("You opponent choose Scissor")
        print("You tied")
        
if timing == "2":
    choice = input("Choose Rock, Paper, Scissor..........")

    if choice == "rock":
        print("Your opponet choose Rock")
        print("You tied")
    
    elif choice == "paper":
        print("Your opponent choose paper")
        print("You tied")
    
    
    elif choice == "scissor":
        print("You opponent choose Scissor")
        print("You tied")
        
if timing == "3":
    choice = input("Choose Rock, Paper, Scissor..........")

    if choice == "rock":
        print("Your opponet choose scissor")
        print("You won")
    
    elif choice == "paper":
        print("Your opponent choose rock")
        print("YOu won")
    
    
    elif choice == "scissor":
        print("You opponent choose paper")
        print("YOu won")
