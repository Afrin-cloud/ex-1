# ex-1
Challenge
 Many people keep time using a 24 hour clock (11 is 11am and 23 is 11pm, 0 is midnight). If it is currently 13 and you set your alarm to go off in 50 hours, it will be 15 (3pm). Write a Python program to solve the general version of the above problem. Ask the user for the time now (in hours), and then ask for the number of hours to wait for the alarm. Your program should output what the time will be on the clock when the alarm goes off.
 time_now=float(input("please enter time now: "))
alarm_set=float(input("please enter the number of hours to wait for the alarm: "))
print("The time will be:", (time_now+alarm_set)%24)
