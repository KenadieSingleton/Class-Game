# Class-Game
play = True
start ='''
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    |    You get up in the morning and you're walking to school.        |
    |    A person in front of you is also walking to school,            |
    |    you can tell they go to the same school by the logo on their   |
    |    bag, but you have never seen them before. You notice that they |
    |    dropped a book but did not notice. Do you leave it, or pick it |
    |     up and give it to them?                                       |
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    '''
work ='''
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    |    In class you are given an assignment                               |
    |    and given the rest of the class to work on it. Do you work on your |
    |    assignment, or chill out for the rest of class and do it at home?  |
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    Type ‘work on it’ to get a head start, or ‘do at home’ to do later
        '''
lunch = '''
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    |    The bell for lunch rings and you enter the hall to enjoy that jammin       |
    |    pb n j you whipped up at home with flare                                   |
    |    you enter the cafeteria and see your friends in their                      |
    |    signiture spot, but you also see the new student from this morning         |
    |     you sitting alone. Do you sit next to the new kid, invite the new kid over|
    |    to your table with your friends, or go to your table?                      |
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

    Type 'sit next to' to sit with them, 'invite' to bring them to your table
    with your friends, or 'go to table' to go sit with your friends
    '''
lunch2 = '''
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    |    The bell for lunch rings and you enter the hall to enjoy that jammin    |
    |    pb n j you whipped up at home with flare                                |
    |    you enter the cafeteria and see your friends in their                   |
    |    signiture spot, but you also see Alex sitting alone reading their book. |
    |    Do you sit next to Alex, invite them over                               |
    |    to your table with your friends, or go to your table?                   |
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
        Type 'sit next to' to sit with them, 'invite' to bring them to your table
        with your friends, or 'go to table' to go sit with your friends
        '''
after = '''
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    |    The bell rings, signaling the end of the school day           |
    |    you have some time before your parents comes to pick you      |
    |    up, do you want to go finish the assignment from class, or go |
    |    hang out with your friends in the cafeteria?                  |
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

        Type 'work' to work on the assignment, or 'hang out' to hang out
        with your friends
        '''
home1 ='''
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    |    As you make your way to your parents' car, you see Alex leaving as well       |
    |    and they are talking to another student very excitedly. When Alex sees you    |
    |    they come over and introduce you to their friend. Alex tells you that you     |
    |    inspired them to be more social, which lead to them meeting their new friend. |
    |    You congradulate them as you both say goodbye.                                |
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
        '''
home2 ='''
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    |    As you make your way to your parents' car, you see the student from      |
    |    this morning leaving as well, but they look very sad as they board their |
    |    car. You go into your car, thinking how you maybe could have approached  |
    |    them earlier.                                                            |
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
        '''
home3 ='''
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    |    As you make your way to your parents' car, you see Alex sitting outside |
    |    reading their book alone. You go into your car, thinking how you maybe  |
    |    could have approached them at earlier at lunch so they wouldn't look    |
    |    so lonely.                                                              |
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
        '''

while play:

    print(start)

    print("Type 'leave it' to leave the book on the ground or 'pick up' to pick up the book")

    user_input = input()

    while user_input not in ("leave it", "pick up"):
        user_input = input("Invalid. Enter again: ")

    if user_input == "leave it":
        print("-------------------------------------------------------")
        print("You decide to leave it and continue on your way to school. You enter school and")
        print("go to class.")
        print(work)

        user_input = input()

        while user_input not in ("work on it", "do at home"):
            user_input = input("Invalid. Enter again: ")

        if user_input == "work on it":
            print("------------------------------------------------")
            print("You begin to work on the assignment and get a decent chunk of it done.")
            print(lunch)

            user_input = input()

            while user_input not in ("sit next to", "invite","go to table"):
                user_input = input("Invalid. Enter again: ")

            if user_input == "sit next to":
                print("--------------------------------------------")
                print("you sit next to the new kid and ask their name so you")
                print("can stop calling them 'new kid'. they tell you their name is Alex")
                print("They seem very quiet, so you ask about them and have a conversation")
                print("They tell you that they are a little bummed because they lost")
                print("their text book, and you feel a little guilty as you think")
                print("back to the book you left on the ground.you have a nice")
                print("conversation and enjoy the rest of lunch with Alex. They thank you for sitting")
                print("next to them, and explain that they have a hard time being social")
                print("and they really appreciate it")
                print("You exchange numbers with Alex and tell them goodbye")
                print("as you head to your last class.")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to finish off the assignment")
                    print("since you got a lot of it done in class. You finish it")
                    print("and you feel relief knowing now you can go home and chill")

                    print(home1)

                    print("When you get home you enjoy the rest of the afternoon to")
                    print("yourself and do what ever it is you like to do for fun in your")
                    print("free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you have a good time goofing around with them before you")
                    print("have to leave")

                    print(home1)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

            elif user_input == "invite":
                print("-------------------------")
                print("You invite the new kid to your table with your friends. The table")
                print("introduces themselves to the new kid, and the kid says their name")
                print("is Alex. You All enjoy lunch together and Alex thanks you for inviting")
                print("them. They tell you they were feeling a little down because they lost their book")
                print("this morning. You feel guilt as you remember the book on the ground")
                print("from this morning that you didn't pick up.")
                print("you say goodbye to your friends and Alex as you head to your last class")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home1)

                    print("When you get home you enjoy the rest of the afternoon to")
                    print("yourself and do what ever it is you like to do for fun in your")
                    print("free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you see Alex with them laughing and having fun. You join them")
                    print("and have a good time goofing around with them before you have to leave")

                    print(home1)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

            elif user_input == "go to table":
                print("--------------------------------")
                print("You walk past them and head to your table, but as you do you")
                print("notice the student looks really sad")
                print("You chat with your friends and enjoy lunch together before it's")
                print("time to go to the last class")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home2)

                    print("When you get home you enjoy the rest of the afternoon to")
                    print("yourself and do what ever it is you like to do for fun in your")
                    print("free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

                elif user_input == "hang out":

                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you have a good time goofing around with them before you")
                    print("have to leave")

                    print(home2)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

        elif user_input == "do at home":

            print("------------------------------------------------")
            print("You decide to save the assignment for later and talk with your friends")
            print("about teenager stuff that teenagers talk about")

            print(lunch)

            user_input = input()

            while user_input not in ("sit next to", "invite","go to table"):
                user_input = input("Invalid. Enter again: ")

            if user_input == "sit next to":

                print("--------------------------------------------")
                print("you sit next to the new kid and ask their name so you")
                print("can stop calling them 'new kid'. they tell you their name is Alex")
                print("They seem very quiet, so you ask about them and have a conversation")
                print("They tell you that they are a little bummed because they lost")
                print("their text book, and you feel a little guilty as you think")
                print("back to the book you left on the ground.you have a nice")
                print("conversation and enjoy the rest of lunch with Alex. They thank you for sitting")
                print("next to them, and explain that they have a hard time being social")
                print("and they really appreciate it")
                print("You exchange numbers with Alex and tell them goodbye")
                print("as you head to your last class.")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home1)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you have a good time goofing around with them before you")
                    print("have to leave")

                    print(home2)

                    print("When you get home, you start on the assignment and don't")
                    print("finish until it's almost 10 o'clock. You have to go to bed")
                    print("late and don't get to have any free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

            elif user_input == "invite":

                print("------------------------------------------------")
                print("You invite the new kid to your table with your friends. The table")
                print("introduces themselves to the new kid, and the kid says their name")
                print("is Alex. You All enjoy lunch together and Alex thanks you for inviting")
                print("them. They tell you they were feeling a little down because they lost their book")
                print("this morning. You feel guilt as you remember the book on the ground")
                print("from this morning that you didn't pick up.")
                print("you say goodbye to your friends and Alex as you head to your last class")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home1)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you see Alex with them laughing and having fun. You join them")
                    print("and have a good time goofing around with them before you have to leave")

                    print(home2)

                    print("When you get home, you start on the assignment and don't")
                    print("finish until it's almost 10 o'clock. You have to go to bed")
                    print("late and don't get to have any free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

            elif user_input == "go to table":

                print("------------------------------------------------")
                print("You walk past them and head to your table, but as you do you")
                print("notice the student looks really sad")
                print("You chat with your friends and enjoy lunch together before it's")
                print("time to go to the last class")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home2)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                         play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you have a good time goofing around with them before you")
                    print("have to leave")

                    print(home2)

                    print("When you get home, you start on the assignment and don't")
                    print("finish until it's almost 10 o'clock. You have to go to bed")
                    print("late and don't get to have any free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                         play = True


    elif user_input == "pick up":
        print("-------------------------------")
        print("You pick up the book and hand it to the student who looks suprised and")
        print("thanks you heavily. You ask them they're name and they tell you its Alex.")
        print("You and Alex talk and converse all the way to school until you have to go")
        print("to your own classes")
        print(work)

        user_input = input()

        while user_input not in ("work on it", "do at home"):
            user_input = input("Invalid. Enter again: ")

        if user_input == "work on it":
            print("------------------------------------------------")
            print("You begin to work on the assignment and get a decent chunk of it done.")
            print(lunch2)

            user_input = input()

            while user_input not in ("sit next to", "invite","go to table"):
                user_input = input("Invalid. Enter again: ")

            if user_input == "sit next to":
                print("--------------------------------------------")
                print("you sit next Alex and continue the conversation you had with them")
                print("this morning and enjoy the rest of lunch with them.")
                print("They thank you for sitting next to them, and explain that they")
                print("have a hard time being social and they really appreciate it")

                print(after)


                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")



                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to finish off the assignment")
                    print("since you got a lot of it done in class. You finish it")
                    print("and you feel relief knowing now you can go home and chill")

                    print(home1)

                    print("When you get home you enjoy the rest of the afternoon to")
                    print("yourself and do what ever it is you like to do for fun in your")
                    print("free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                         play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you have a good time goofing around with them before you")
                    print("have to leave")

                    print(home1)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                         play = True

            elif user_input == "invite":
                print("---------------------------------------")
                print("You invite Alex to your table with your friends. The table")
                print("introduces themselves to them. You all enjoy lunch together and")
                print("Alex thanks you for inviting them.")
                print("You say goodbye to your friends and Alex as you head to your last class")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home1)

                    print("When you get home you enjoy the rest of the afternoon to")
                    print("yourself and do what ever it is you like to do for fun in your")
                    print("free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                         play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you see Alex with them laughing and having fun. You join them")
                    print("and have a good time goofing around with them before you have to leave")

                    print(home1)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                         play = True

            elif user_input == "go to table":
                print("---------------------------------------")
                print("You walk past them and head to your table as they continue reading.")
                print("You chat with your friends and enjoy lunch together before it's")
                print("time to go to the last class")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home3)

                    print("When you get home you enjoy the rest of the afternoon to")
                    print("yourself and do what ever it is you like to do for fun in your")
                    print("free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                         play = True

                elif user_input == "hang out":

                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you have a good time goofing around with them before you")
                    print("have to leave")

                    print(home3)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                         play = True

        elif user_input == "do at home":

            print("------------------------------------------------")
            print("You decide to save the assignment for later and talk with your friends")
            print("about teenager stuff that teenagers talk about")

            print(lunch2)

            user_input = input()

            while user_input not in ("sit next to", "invite","go to table"):
                user_input = input("Invalid. Enter again: ")

            if user_input == "sit next to":

                print("--------------------------------------------")
                print("you sit next Alex and continue the conversation you had with them")
                print("this morning and enjoy the rest of lunch with them.")
                print("They thank you for sitting next to them, and explain that they")
                print("have a hard time being social and they really appreciate it")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home1)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                            play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you have a good time goofing around with them before you")
                    print("have to leave")

                    print(home1)

                    print("When you get home, you start on the assignment and don't")
                    print("finish until it's almost 10 o'clock. You have to go to bed")
                    print("late and don't get to have any free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

            elif user_input == "invite":
                print("---------------------------------------")
                print("You invite Alex to your table with your friends. The table")
                print("introduces themselves to them. You all enjoy lunch together and")
                print("Alex thanks you for inviting them.")
                print("You say goodbye to your friends and Alex as you head to your last class")

                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home1)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you see Alex with them laughing and having fun. You join them")
                    print("and have a good time goofing around with them before you have to leave")


                    print(home1)

                    print("When you get home, you start on the assignment and don't")
                    print("finish until it's almost 10 o'clock. You have to go to bed")
                    print("late and don't get to have any free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

            elif user_input == "go to table":

                print("------------------------------------------------")
                print("You walk past them and head to your table as they continue reading.")
                print("You chat with your friends and enjoy lunch together before it's")
                print("time to go to the last class")


                print(after)

                user_input = input()

                while user_input not in ("work", "hang out"):
                    user_input = input("Invalid. Enter again: ")

                if user_input == "work":
                    print("--------------------------------------------")
                    print("You go some place quiet to start the assignment")
                    print("You get a good chunk of it done before you have to go home")

                    print(home3)

                    print("When you get home, you finish the assignment from earlier.")
                    print("After you finish, you have a little bit of time to do what ever")
                    print("you do for fun in your free time, although you have to bed soon")
                    print("after.")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True

                elif user_input == "hang out":
                    print("--------------------------------------------")
                    print("You go to the cafeteria to hang out with your friends and")
                    print("you have a good time goofing around with them before you")
                    print("have to leave")

                    print(home3)

                    print("When you get home, you start on the assignment and don't")
                    print("finish until it's almost 10 o'clock. You have to go to bed")
                    print("late and don't get to have any free time")

                    print("END")

                    again=str(input("Do you want to play again, type yes or no "))

                    if again == "no":
                         print("Thanks for playing!")
                         play = False

                    elif again =="yes":
                        play = True
