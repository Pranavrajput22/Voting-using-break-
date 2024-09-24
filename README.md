# Voting-using-break-

BHAJPA, CONG, GOATS = 0, 0, 0
while True:
    v = int(input("Enter your age: "))
    if v >= 18:
        print("Press 1 for BJP")
        print("Press 2 for Congress")
        print("Press 3 for GOATS")
        c = int(input("Enter your choice: "))
    if c == 1:
            BHAJPA += 1
        elif c == 2:
            CONG += 1
        elif c == 3:  
            GOATS += 1
        else:
            print("Invalid choice. Please try again.")
            print("Total Vote of BJP = ", BHAJPA)
            print("Total Vote of Congress = ", CONG)
            print("Total Vote of AAP = ", GOATS)
            cont = input("Do you want to continue voting? (yes/no): ")
        if cont.lower() != "yes":
            break
       else:
           print("You are not eligible to vote.")
