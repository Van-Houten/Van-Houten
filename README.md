import time
import random

use_counter=0
room_counter=0
left_counter=0
forward_counter=0
right_counter=0
backward_counter=0
ts0=0
ts1=1
ts2=2
ts3=3
ts4=4
ts5=5

time.sleep(ts2)
print('Hello...')
time.sleep(ts3)
print('You are new, arent ya?')
time.sleep(ts3)
print('Oh where are my manners?')
time.sleep(ts3)
print('At first i should introduce myself...')
a=input('Im Larris, who are you?: ')
print('Ahh ok...')
time.sleep(ts3)
print(a,', what a beautiful name')
time.sleep(ts2)
reset1=print('...')
time.sleep(ts2)
b=input('Do you wanna play this game ' + a +'?(y/n): ')
if b=='y':
    time.sleep(ts2)
    print('GOOD')
    time.sleep(2)
    print('Very Well',a)
    time.sleep(ts2)
    print('BUT before we start, some formalities...')
    time.sleep(ts2)
    b=input('DO YOU KNOW ANY SECRET CODES???(y/n): ')
    if b=='n':
        time.sleep(ts2)
        print('...')
        time.sleep(ts2)



####################SECRET CODES

        
    if b=='y':
        b=input('Please insert the Code '+a+': ')
        if b=='73002':
            ts2=0
            print('SKIP')
            time.sleep(2)


####################SECRET CODES



            
        else:
            time.sleep(ts2)
            print('')
            print('OK you dont')
            print('')
            time.sleep(ts2)
    

elif b=='n':
    time.sleep(ts2)
    print('...')
    time.sleep(ts2)
    print('Ok ill close it')
    time.sleep(ts2)
    while True:
        quit()
else:
    time.sleep(ts2)
    print('This isnt even an answer...')
    time.sleep(ts2)
    print('YOU arent worthy to play this game')
    time.sleep(ts2)
    print('Bye')
    while True:
        quit()
    
print('OK')
time.sleep(ts2)
print("You'll wake up now...")
time.sleep(ts2)
print('SYSTEM UNIT ACTIVATED')
time.sleep(ts2)
print('LIFE SPECIMEN KNOW AS '+a+'.SECRETNUMBER73002 AWAKE')
time.sleep(ts2)
print('USE "help" TO SEE YOUR FEASIBILITYS')

ts2=2


######################task 1

while True:
    b=input('unknown location>> ')
    if b=='help':
        print('')
        time.sleep(2)
        print('look around, go left, go right, go forward, go backward, use')
        print('')
    if b=='look around':
        print('')
        time.sleep(2)
        print('You can see machines... they and you are in a brightly lit room. \
To your left is a piece of paper, but you cant see what is written on it. \
Infront of you is a machine with different lamps in different colors. \
To your right is a door''')
        print('')
    if b=='go left':
        print('')
        time.sleep(2)
        print('"28437".... thats the number that you can read on the paper')
        print('')
    if b=='go forward':
        time.sleep(2)
        print('')
        print('Theres a paper... you can see: "numRnumGnumBnumGnumR" written on it')
        print('')
    if b=='go backward':
        time.sleep(2)
        print('You bump into a container that seems you have come out of it...')
    if b=='go right':
        print('')
        time.sleep(2)
        print('There is a door with a keypad...')
        print('')
        b=input('keypad>> ')
        print('')
        if b=='use':
            b=input('keypad_input>> ')
            if b=='2R8G4B3G7R':
                print('')
                print('ACCESS GRANTED')
                print('')
                time.sleep(3)
                print('You enter a new room...')
                time.sleep(100000)
            else:
                print('')
                print('ACCESS DENIED')
                print('')
        else:
            print('NOT POSSIBLE')
            print('')

######################task 1

print('SOMETHING FATAL WENT WRONG')
quit()
