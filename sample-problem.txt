#This is a countdown from an integer program using Python 3.4.0#

#A string value is assigned to 'first_num' while user sees on the screen 'Please input first number'#
first_num = input("Please input first number: ")
#A string value is assigned to 'sec_num' while user sees on the screen 'Please input second number'#
sec_num = input("Please input second number: ")
#'first_num' and 'sec_num' are added and converted from string to integer and stored into answer variable#
answer = int(first_num) + int(sec_num)
#Output on screen will show 'Now I will add your two numbers' and then output int variable stored in answer#
print ("Now I will add your two numbers:", answer)
#Output on screen 'Pretty cool, huh?'#
print ("Pretty cool, huh?")
#Output on screen 'Now I'll count backwards from' and then output int variable stored in answer#
print ("Now I'll count backwards from", answer)
#Convert answer value from string to integer due to while loop. int answer stored in counter variable#
counter = int(answer)
#While loop of value stored in counter counts down to zero#
while (counter >= 0):
#Output on screen 'counter' value#
 print (counter)
#Decrement by one for every iteration of while loop by -1#
 counter = counter - 1
#Output on screen 'All done' until value reaches 0#
print ("All done!")

#ANSWER#
#Python 3.4.0 (default, Apr 11 2014, 13:05:11)
#
#Please input first number:  5
#Please input second number:  2
#Now I will add your two numbers: 7
#Pretty cool, huh?
#Now I'll count backwards from 7
#7
#6
#5
#4
#3
#2
#1
#0
#All done!
#=> None
