# 210CT-Coursework
coursework

import random

# create new list 
listX = []

def shuffle(numberList):

    print ('Array of Numbers:', numberList)

    for i in range(len(numberList)):

        randomValue = random.choice(numberList)
        listX.append(randomValue) #modifying the list
        numberList.remove(randomValue)

    print ('\nRandom Array of Numbers:', listX)
# adding elements to the original list
numberList = ['1', '2', '3', '4', '5', '6']
shuffle(numberList)

