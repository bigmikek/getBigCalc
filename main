def intro():
    name = input("\n\n\n\n\n\n\n\n\n\n\n\n\nHello, I am Kriten, your fitness Artificial Intellegince. What is your name? \n\n\n\n\n")
    print("\nThank you ", name)
    return

def orm():
    try:
        weight = input("Enter weight in pounds: ")
        weight_t = int(weight)
        reps = input("Enter the number of successful reps: ")
        reps_t = int(reps)
        max_scale_factor = 1/30

        ORM = (reps_t * weight_t * max_scale_factor) + weight_t

        base = 5

        True_ORM = base * round(ORM/base)

        print("Your ORM based on given inputs is ", True_ORM)
        gram()
    except:
        print("idiot")
        gram()
    return

def plan():
    plan = input("Do you want to Bulk, Cut, or go back? ")

    if plan == 'Bulk' or plan == 'bulk':
        print("Do a 5x5 rep schema focused on the core 4 lifts ")
        gram()
    elif plan == 'Cut' or plan == 'cut':
        print("Go run fatty ")
        gram()
    elif plan == 'back':
        gram()
        
    else:
        print("invalid response, run the program again ")
        plan()
    return

def info():
        weight = int(input("What is your weight in lbs? "))
        heightf = int(input("what is your height in feet? "))
        heighti = int(input("What is your remaining height in inches? "))
        heightt = (heightf*12)+heighti
        heightc = heightt * 2.54
        weightk = weight/2.205
        bmi = round(10000*(weightk/(heightc*heightc)),1)
        print("with the given info, your bmi is ", bmi)
        gram()
        return
        
def gram():
    fun = input("\nChoose ORM, Plan, dab, or input info \n")
    if fun == 'ORM' or fun == 'orm':
        try:
            orm()
        except:
            print("You had one job smh", name)
            gram()
    elif fun =='Plan' or fun == 'plan':
        plan()
    elif fun == 'info':
        info()
    elif fun == 'dab':
        dab()
    else:
        print("Invalid Response, try again")
        gram()
    return
def dab():
    num = 0
    try:
        lensize = int(input("How many days a week would you like to train? "))
        if lensize > 7 or lensize < 1:
            print("invalid number, please try again")
            dab()
        elif lensize == 7:
            print("Bruh too much")
            gram()
        else:
            sun = input("Would you like to train Sunday? Answer y/n: ")
            if sun == 'y':
                num = num + 1
                sunt = 1
            else:
                sunt = 0
            mon = input("Would you like to train Monday? Answer y/n: ")
            if mon == 'y':
                num = num +1
                mont = 1
            else:
                mont = 0
            tues = input("Would you like to train Tuesday? Answer y/n: ")
            if tues == 'y':
                num = num +1
                wedt = 1
            else:
                tuest = 0
            wed = input("Would you like to train Wednesday? Answer y/n: ")
            if wed == 'y':
                num = num +1
                wedt = 1
            else:
                wedt = 0
            thur = input("Would you like to train Thursday? Answer y/n: ")
            if thur == 'y':
                num = num +1
                thurt = 1
            else:
                thurt = 0
            fri = input("Would you like to train Friday? Answer y/n: ")
            if fri == 'y':
                num = num +1
                frit = 1
            else:
                frit = 0
            sat = input("Would you like to train Saturday? Answer y/n: ")
            if sat == 'y':
                num = num +1
                satt = 1
            else:
                satt = 0
            if num != lensize:
                print("You selected an invalid amount of days! ")
                dab()
            else:
                if num == 1:
                    print("I suggest a full body routine for a 1 day a week lifting plan ")
                elif num == 2:
                    print("I suggest a full body routine with alternating heavy Squat and Deadlift days for a 2 day a week lifting plan")
                elif num == 3:
                    print("I suggest spending a day on bench, squat and deadlift with alternating chest and shoulders every 1st day of the cycle ")
                elif num == 4:
                    print("I suggest spending a day concentrating on 1 of the 4 excersises ")
                elif num == 5:
                    print ("I suggest spending time ")
                else:
                    print("I suggest suffering")
                days = ["monday",'tuesday','wednesday','thursday','friday','saturday']
                print("the days you want to lift are", days)
    except:
        print("invalid response, please try again")
        dab()
intro()
gram()
